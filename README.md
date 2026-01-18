<!DOCTYPE html>
<html>
<head>
  <title>Kartu Stok</title>
</head>
<body>
  <iframe 
    src="https://script.google.com/macros/s/AKfycbx0qVg7qeW9V0TZqQtiMCxchRbaUWTwc5E3r3Wqq7XRpsds_pUisiuz54BhwrRD79Me/exec"
    width="100%"
    height="100%"
    allowfullscreen="true"
    style="position: fixed; top: 0; left: 0; width: 100%; height: 100%; border: none;">
  </iframe>

  <script>
    window.onload = function() {
      document.querySelector('iframe')
        .requestFullscreen()
        .catch((err) => {
          console.error('Error attempting to enable full-screen mode:', err.message);
        });
    };
  </script>
</body>
</html>
