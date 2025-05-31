<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Super Fun Game</title>
  <style>
    body, html {
      margin: 0; padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #121212;
      color: white;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .container {
      padding: 20px;
      text-align: center;
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
      font-weight: 900;
    }
    p {
      font-size: 1.2em;
      margin-bottom: 25px;
      color: #bbb;
    }
    img {
      max-width: 90%;
      border-radius: 15px;
      margin-bottom: 25px;
      box-shadow: 0 0 15px #ff3c00;
    }
    .btn-download {
      background: #ff3c00;
      color: white;
      padding: 18px 40px;
      font-size: 1.3em;
      border: none;
      border-radius: 35px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 5px 15px #ff3c00aa;
      transition: background 0.3s ease;
      text-decoration: none;
      display: inline-block;
      margin-bottom: 30px;
    }
    .btn-download:hover {
      background: #e63600;
    }
    footer {
      background: #222;
      padding: 15px;
      font-size: 0.9em;
      color: #888;
      text-align: center;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Super Fun Game</h1>
    <p>Aasaan controls, zabardast graphics, aur doston ke saath mazaa!</p>
    <img src="https://via.placeholder.com/300x500.png?text=Game+Screenshot" alt="Game Screenshot" />
    <a href="#" class="btn-download">Abhi Download Karein</a>
  </div>

  <footer>
    &copy; 2025 Super Fun Game. Sabhi adhikar surakshit hain.
  </footer>

</body>
</html>
