<!DOCTYPE html>
<html>
<head>
  <title>Nothing</title>
  <style>
    body {
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #2E3440;
      overflow: hidden;
    }

    .container {
      position: relative;
    }

    .text {
      font-family: Arial, sans-serif;
      font-size: 60px;
      color: #D8DEE9;
      opacity: 0;
      transform: scale(0);
      animation: textAnimation 2s ease-in-out forwards;
    }

    @keyframes textAnimation {
      0% {
        opacity: 0;
        transform: scale(0);
      }
      50% {
        opacity: 1;
        transform: scale(1.2);
      }
      100% {
        opacity: 1;
        transform: scale(1);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="text">NOTHING</h1>
  </div>
</body>
</html>
