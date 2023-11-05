<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background: #000;
      overflow: hidden;
    }

    .neon-circle {
      width: 100px;
      height: 100px;
      border-radius: 50%;
      position: absolute;
      animation: spin 10s linear infinite, neon 2s ease-in-out infinite;
    }

    @keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }

    @keyframes neon {
      0% {
        box-shadow: 0 0 20px #00ff00;
      }
      50% {
        box-shadow: 0 0 20px #ff00ff, 0 0 20px #00ff00;
      }
      100% {
        box-shadow: 0 0 20px #00ff00;
      }
    }
  </style>
</head>
<body>
  <!-- Spinning neon circles -->
  <div class="neon-circle" style="top: 100px; left: 100px;"></div>
  <div class="neon-circle" style="top: 200px; left: 200px;"></div>
  <!-- Add more circles or adjust positions as needed -->

  <!-- Your existing code with an embedded Canva design -->
  <div style="position: relative; width: 100%; height: 0; padding-top: 56.2225%;
    padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63, 69, 81, 0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
    border-radius: 8px; will-change: transform;">
    <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0; margin: 0;"
      src="https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFzPTlYt3M&#x2F;view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
    </iframe>
  </div>
</body>
</html>
