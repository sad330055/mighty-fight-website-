<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MIGHTY FIGHT</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #fff;
      background: url('Banner.png') no-repeat center center fixed;
      background-size: cover;
      overflow: hidden;
    }

    .overlay {
      background: rgba(0, 0, 0, 0.7);
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: 1;
    }

    .container {
      position: relative;
      z-index: 2;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }

    h1 {
      font-size: 4rem;
      letter-spacing: 5px;
      color: #eee;
      animation: slideDown 1s ease-out;
    }

    p {
      font-size: 1.2rem;
      max-width: 700px;
      margin-top: 1rem;
      line-height: 1.6;
      animation: fadeIn 2s ease-in-out 0.5s both;
    }

    .buttons {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      justify-content: center;
      margin-top: 2rem;
    }

    a.button {
      padding: 1rem 2rem;
      background-color: #ff4444;
      color: white;
      text-decoration: none;
      font-weight: bold;
      border-radius: 8px;
      transition: transform 0.3s ease, background 0.3s ease;
    }

    a.button:hover {
      background-color: #cc0000;
      transform: scale(1.05);
    }

    .discord-icon {
      width: 40px;
      height: 40px;
      vertical-align: middle;
      margin-right: 8px;
    }

    footer {
      position: absolute;
      bottom: 20px;
      width: 100%;
      text-align: center;
      font-size: 0.9rem;
      color: #bbb;
      z-index: 2;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideDown {
      from { transform: translateY(-30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <audio autoplay loop>
    <source src="Radiohead - Street Spirit (Fade Out).mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>

  <div class="overlay"></div>
  <div class="container">
    <h1>MIGHTY FIGHT</h1>
    <p>انضم إلى أقوى سيرفر قتالي بنظام مطور ومجتمع نشط 24/7. 
    مغامرات ملحمية، أسلحة متنوعة، وأحداث مثيرة تنتظرك في عالم MIGHTY FIGHT.
    لا تفوت الفرصة وادخل عالمنا الآن!</p>
    <div class="buttons">
      <a class="button" href="https://cfx.re/join/4dgyy9" target="_blank">ادخل السيرفر</a>
      <a class="button" href="https://discord.gg/my2" target="_blank">
        <img class="discord-icon" src="Logo.png" alt="Discord Logo" />انضم للديسكورد
      </a>
    </div>
  </div>
  <footer>
    MIGHTY FIGHT &copy; 2025 - discord.gg/MY2
  </footer>
</body>
</html>


