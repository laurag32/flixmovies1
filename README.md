# flixmovies1
Main page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🎬 Flixmovies</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: Arial, sans-serif;
      color: white;
      background: url('https://via.placeholder.com/1920x1080?text=Cinematic+Backdrop') no-repeat center center fixed;
      background-size: cover;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
      backdrop-filter: brightness(0.4);
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 40px 20px;
      border-radius: 10px;
      max-width: 600px;
      margin: 20px;
    }

    header {
      font-size: 2.5rem;
      font-weight: bold;
      margin-bottom: 20px;
    }

    .description {
      font-size: 1.2rem;
      margin-bottom: 30px;
      line-height: 1.6;
    }

    .buttons {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }

    .buttons a {
      text-decoration: none;
      background-color: #e50914;
      color: white;
      padding: 12px 24px;
      border-radius: 5px;
      font-size: 1rem;
      transition: background-color 0.3s ease;
    }

    .buttons a:hover {
      background-color: #b00610;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9rem;
      color: #aaa;
    }

    @media (max-width: 600px) {
      header {
        font-size: 1.8rem;
      }

      .description {
        font-size: 1rem;
      }

      .buttons a {
        width: 100%;
        max-width: 200px;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <header>🎬 Flixmovies</header>

    <div class="description">
      Access a world of free, high-quality movies.<br />
      <strong>Join our Telegram channel to stream or download the latest hits!</strong>
    </div>

    <div class="buttons">
      <a href="https://t.me/+q8_oxC2w6Zk3OTRk" target="_blank">▶️ Join to Watch</a>
      <a href="https://t.me/+q8_oxC2w6Zk3OTRk" target="_blank">📥 Join to Download</a>
    </div>

    <footer>&copy; 2025 Flixmovies</footer>
  </div>
</body>
</html>
