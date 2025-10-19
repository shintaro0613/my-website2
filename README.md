# my-website2
elearning１１９
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>消防・救急 教育ポータル | Naoki Works</title>
  <style>
    body {
      margin: 0;
      font-family: "Hiragino Sans", "Yu Gothic", sans-serif;
      background: radial-gradient(circle at center, #0a0a0a 0%, #000000 100%);
      color: white;
      text-align: center;
      overflow-x: hidden;
    }

    header {
      padding: 2.5rem 1rem 1rem;
    }

    h1 {
      font-size: 2rem;
      letter-spacing: 0.1em;
      background: linear-gradient(90deg, #ffd700, #ff4500);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      text-shadow: 0 0 25px rgba(255, 180, 0, 0.6);
    }

    p.subtitle {
      font-size: 1.1rem;
      color: #ccc;
      margin-top: 0.5rem;
      text-shadow: 0 0 6px rgba(255,255,255,0.2);
    }

    .grid {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      gap: 2rem;
      padding: 3rem 1rem;
    }

    .card {
      width: 280px;
      height: 220px;
      border-radius: 18px;
      padding: 1.5rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      transition: all 0.4s ease;
      cursor: pointer;
      box-shadow: 0 0 20px rgba(255,255,255,0.15);
      text-decoration: none;
    }

    /* 消防版カード */
    .fire {
      background: linear-gradient(135deg, #111, #330000, #111);
      border: 2px solid #ff3b3b;
      box-shadow: 0 0 30px rgba(255, 90, 0, 0.3);
    }

    .fire:hover {
      transform: scale(1.05);
      box-shadow: 0 0 40px rgba(255, 140, 0, 0.8), 0 0 80px rgba(255, 90, 0, 0.6);
    }

    .fire h2 {
      color: #ffd700;
      text-shadow: 0 0 10px rgba(255, 200, 50, 0.7);
      margin-bottom: 0.5rem;
    }

    .fire p {
      color: #ffcccc;
      font-size: 0.95rem;
    }

    /* 救急版カード */
    .ems {
      background: linear-gradient(135deg, #002b5c, #003b7a, #001f3f);
      border: 2px solid #0074d9;
      box-shadow: 0 0 30px rgba(0, 114, 255, 0.3);
    }

    .ems:hover {
      transform: scale(1.05);
      box-shadow: 0 0 40px rgba(215, 26, 40, 0.8), 0 0 70px rgba(0, 120, 255, 0.6);
    }

    .ems h2 {
      color: #ffffff;
      text-shadow: 0 0 10px rgba(255,255,255,0.8);
      margin-bottom: 0.5rem;
    }

    .ems p {
      color: #dce9ff;
      font-size: 0.95rem;
    }

    footer {
      margin-top: 2rem;
      font-size: 0.85rem;
      color: #777;
      padding-bottom: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>消防・救急 教育ポータル</h1>
    <p class="subtitle">現場で生きる学びを、次の世代へ。</p>
  </header>

  <div class="grid">
    <a href="https://＜消防eラーニング用リポジトリ名＞.github.io/" class="card fire" target="_blank">
      <h2>🚒 消防教育サイト</h2>
      <p>黒×金×赤の高級感で統一された、現場安全・災害対応学習コンテンツ</p>
    </a>

    <a href="https://＜救急eラーニング用リポジトリ名＞.github.io/" class="card ems" target="_blank">
      <h2>🚑 救急教育サイト</h2>
      <p>トリコロールを基調にした、信頼・技術・命の学びポータル</p>
    </a>
  </div>

  <footer>© 2025 消防・救急 教育ポータル / 作成：Naoki</footer>
</body>
</html>
