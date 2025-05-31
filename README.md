<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Arjun Online Book</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background: url('background.png') no-repeat center center/cover;
      height: 100vh;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      position: relative;
    }

    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 0, 0, 0.6);
      z-index: 0;
    }

    .container {
      position: relative;
      z-index: 1;
    }

    .profile-img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
      color: #fff;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 30px;
    }

    .telegram-button {
      background-color: #0088cc;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 30px;
      font-size: 1.1rem;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
      transition: background 0.3s;
    }

    .telegram-button:hover {
      background-color: #006ea8;
    }

    .footer {
      position: absolute;
      bottom: 10px;
      width: 100%;
      text-align: center;
      font-size: 0.9rem;
      color: #ccc;
    }
  </style>
</head>
<body>
  <div class="overlay"></div>

  <div class="container">
    <img src="profile.png" alt="Profile" class="profile-img" />
    <h1>arjunonlinebook</h1>
    <p>Join my Telegram channel and start today!</p>
    <a href="https://t.me/arjunexchane" class="telegram-button" target="_blank">
      🚀 Join on Telegram
    </a>
  </div>

  <div class="footer">
    © 2025 Arjun Online Book. All rights reserved.
  </div>
</body>
</html>
