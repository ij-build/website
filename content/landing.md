<!DOCTYPE html>

<html lang="en">
{{ partial "head.html" . }}

<body class="bg">
  <div id="site-wrapper">
    {{ partial "header.html" . }}

    <div class="jumbotron">
    <div class="outer-div">
    <div class="inner-div">
      <p>Reproducible builds in Docker</p>

      <div>
        <a class="btn btn-lg btn-primary" href="{{ .Site.BaseURL }}/docs" role="button"><i class="fas fa-laptop-code mr"></i> Build Locally</a>
        <a class="btn btn-lg btn-info" href="https://ijci.ij-build.dev" role="button"><i class="fas fa-cloud mr"></i> Build in the Cloud</a>
      </div>

      <p>One environment, everywhere</p>
    </div>
    </div>
    </div>
  </div>

  {{ .Scratch.Set "attribution" true }}
  {{ partial "footer.html" . }}
</body>
</html>
