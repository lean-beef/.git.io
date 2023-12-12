<!DOCTYPE html>
<html>
<head>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
  <div class="container text-center mt-5">
    <h1>Progress Bar</h1>

    <div class="progress">
      <div class="progress-bar" id="progressBar"></div>
    </div>

    <div class="justify-content-center mt-3">
      <button class="btn btn-danger text-white" style="margin-right: 20px;" onclick="updateProgressBar(33)">33%</button>
      <button class="btn btn-danger text-white" style="margin-right: 20px;" onclick="updateProgressBar(66)">66%</button>
      <button class="btn btn-danger text-white" onclick="updateProgressBar(100)">100%</button>
    </div>
  </div>

  <script>
    function updateProgressBar(percentage) {
      document.getElementById('progressBar').style.width = percentage + '%';
    }
  </script>
</body>
</html>
