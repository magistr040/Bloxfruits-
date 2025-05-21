# Bloxfruits-<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Blox Fruits</title>
  <style>
    body {
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
    }
    .btn {
      font-size: 24px;
      padding: 15px 30px;
      background-color: #1abc9c;
      color: white;
      border: none;
      border-radius: 12px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background-color: #16a085;
    }
  </style>
</head>
<body>
  <h1>Добро пожаловать на Blox Fruits!</h1>
  <p>Для продолжения подтвердите, что вы не робот</p>
  <button class="btn" onclick="rickroll()">Вы не робот</button>

  <script>
    function rickroll() {
      window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
    }
  </script>
</body>
</html>
