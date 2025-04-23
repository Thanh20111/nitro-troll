<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>You've been gifted Nitro!</title>
  <style>
    body {
      background-color: #2c2f33;
      color: #ffffff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }

    .card {
      background-color: #23272a;
      padding: 2rem;
      border-radius: 1rem;
      box-shadow: 0 0 20px rgba(0,0,0,0.5);
      text-align: center;
      width: 90%;
      max-width: 400px;
      position: relative;
    }

    .button {
      background-color: #5865f2;
      color: white;
      border: none;
      padding: 1rem 2rem;
      border-radius: 0.5rem;
      font-size: 1.1rem;
      cursor: pointer;
      margin-top: 1.5rem;
    }

    .button:hover {
      background-color: #4752c4;
    }

    .nitro-img {
      width: 100px;
      margin-bottom: 1rem;
      animation: float 2s ease-in-out infinite;
    }

    /* Logo Nitro bay lơ lửng nhẹ nhàng */
    @keyframes float {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
    }
  </style>
</head>
<body>
  <div class="card">
    <!-- Logo Nitro động -->
    <img src="https://cdn.discordapp.com/attachments/1089873814128312410/1229412425154328616/nitro.png" class="nitro-img" alt="Nitro Gift">
    <h2>You've been gifted 1 Year of Discord Nitro!</h2>
    <p>Click below to claim your gift:</p>
    <button class="button" onclick="window.location.href='https://www.youtube.com/watch?v=3tmsbXgPZOc'">Claim Gift</button>
  </div>
</body>
</html>
