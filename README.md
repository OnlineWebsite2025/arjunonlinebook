<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name - Join Now</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Arial', sans-serif;
    }

    body {
      background: url('https://images.unsplash.com/photo-1557683316-973673baf926?auto=format&fit=crop&w=1920&q=80') no-repeat center center/cover;
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
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 30px;
    }

    .whatsapp-button {
      background-color: #25D366;
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

    .whatsapp-button:hover {
      background-color: #1eb64f;
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
    <img src="https://via.placeholder.com/150" alt="Profile" class="profile-img" />
    <h1>Your Name</h1>
    <p>Join my team and start earning today!</p>
    <a href="https://wa.me/919999999999" class="whatsapp-button" target="_blank">
      💬 Join on WhatsApp
    </a>
  </div>

  <div class="footer">
    © 2025 YourName. All rights reserved.
  </div>
</body>
</html>
