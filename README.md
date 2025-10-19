<style>
  body {
    background-color: #000;
    font-family: 'Hiragino Sans','Yu Gothic',sans-serif;
    color: #d4af37;
    margin: 0;
    padding: 0;
    text-align: center;
  }
  .container {
    padding: 40px 20px;
  }
  h1 {
    font-size: 2rem;
    letter-spacing: 0.08em;
    color: #ff3b3b;
    text-shadow: 0 0 10px #ff0000, 0 0 20px #d4af37, 0 0 40px #ff0000;
    margin-bottom: 10px;
  }
  p.subtitle {
    font-size: 1.1rem;
    color: #d4af37;
    text-shadow: 0 0 5px #b8860b;
  }
  .divider {
    height: 2px;
    background: linear-gradient(90deg, #ff0000, #d4af37, #ff0000);
    width: 80%;
    margin: 30px auto;
    border-radius: 2px;
  }
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    max-width: 950px;
    margin: 0 auto;
  }
  .card {
    background: radial-gradient(circle at 20% 20%, #111 0%, #000 100%);
    border: 1px solid #d4af37;
    border-radius: 12px;
    padding: 25px 15px;
    box-shadow: 0 0 10px rgba(212,175,55,0.4);
    transition: transform 0.3s, box-shadow 0.3s;
  }
  .card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 25px rgba(255, 50, 50, 0.8), 0 0 50px rgba(212,175,55,0.6);
  }
  .lesson-title {
    color: #ff3b3b;
    font-size: 1.2rem;
    font-weight: bold;
    text-shadow: 0 0 10px #ff0000;
  }
  .lesson-desc {
    color: #d4af37;
    font-size: 0.95rem;
    margin: 0.5em 0 1em;
  }
  a.button {
    display: inline-block;
    color: #000;
    background: linear-gradient(135deg, #ffd700, #ffcc33);
    padding: 8px 18px;
    border-radius: 6px;
    font-weight: bold;
    text-decoration: none;
    transition: 0.3s;
  }
  a.button:hover {
    background: linear-gradient(135deg, #ff4d4d, #d4af37);
    color: #fff;
    box-shadow: 0 0 10px #ff0000, 0 0 20px #d4af37;
  }
  footer {
    font-size: 0.85rem;
    color: #777;
    margin-top: 40px;
  }
</style>

<div class="container">
  <h1>🚒 消防 eラーニングポータル</h1>
  <p class="subtitle">現場力を磨く。安全・確実・迅速な行動のために。</p>
  <div class="divider"></div>

  <div class="grid">
    <!-- 各Lesson -->
    <div class="card">
      <div class="lesson-title">Lesson 1</div>
      <div class="lesson-desc">火災現場の安全管理</div>
      <a href="lesson1/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 2</div>
      <div class="lesson-desc">救助活動の基本</div>
      <a href="lesson2/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 3</div>
      <div class="lesson-desc">通信管理・無線運用</div>
      <a href="lesson3/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 4</div>
      <div class="lesson-desc">車両運用と安全走行</div>
      <a href="lesson4/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 5</div>
      <div class="lesson-desc">機械器具の取扱い</div>
      <a href="lesson5/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 6</div>
      <div class="lesson-desc">火災調査と関係法令</div>
      <a href="lesson6/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 7</div>
      <div class="lesson-desc">伐木作業（チェーンソー）特別教育</div>
      <a href="lesson7/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 8</div>
      <div class="lesson-desc">感染防止対策</div>
      <a href="lesson8/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 9</div>
      <div class="lesson-desc">危険物火災対応</div>
      <a href="lesson9/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 10</div>
      <div class="lesson-desc">水難救助</div>
      <a href="lesson10/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 11</div>
      <div class="lesson-desc">心理対応・住民支援</div>
      <a href="lesson11/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 12</div>
      <div class="lesson-desc">無線通信障害対応</div>
      <a href="lesson12/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 13</div>
      <div class="lesson-desc">訓練指導法</div>
      <a href="lesson13/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 14</div>
      <div class="lesson-desc">機関員教育</div>
      <a href="lesson14/index.html" class="button">▶ 学習する</a>
    </div>
    <div class="card">
      <div class="lesson-title">Lesson 15</div>
      <div class="lesson-desc">リーダーシップ</div>
      <a href="lesson15/index.html" class="button">▶ 学習する</a>
    </div>
  </div>

  <div class="divider"></div>
  <footer>© 2025 消防eラーニングサポート / 作成：Naoki</footer>
</div>
