<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f2f2f2;
      color: #333;
      padding: 20px;
    }
    h1 {
      color: #4CAF50;
    }
    img {
      width: 200px;
      border-radius: 10px;
    }
    a {
      color: #0066cc;
      text-decoration: none;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Welcome to My Webpage</h1>
  <p>This is a paragraph to learn basic HTML structure.</p>

  <img src="https://via.placeholder.com/200" alt="Sample Image">

  <p>Visit <a href="https://www.example.com" target="_blank">Example Website</a></p>

  <button onclick="showMessage()">Click Me</button>

  <script>
    function showMessage() {
      alert("Hello! You clicked the button.");
    }
  </script>

</body>
</html>
