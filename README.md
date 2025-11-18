# daizen<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Daichi's Portfolio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Rajdhani:wght@500&family=Noto+Sans+JP:wght@400;500&display=swap');

    body {
      font-family: 'Noto Sans JP', sans-serif;
      margin: 0;
      background-color: #0f1115;
      color: #e0e0e0;
      line-height: 1.8;
    }

    /* ===== Header ===== */
    header {
      position: relative;
      height: 65vh;
      background: url('lego_collection.jpg') center/cover no-repeat;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      color: #fff;
    }

    header::after {
      content: '';
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.55);
    }

    header h1 {
      position: relative;
      font-family: 'Rajdhani', sans-serif;
      font-size: 3rem;
      color: #1abc9c;
      letter-spacing: 2px;
      z-index: 1;
    }

    header p {
      position: relative;
      font-size: 1.1rem;
      color: #ccc;
      z-index: 1;
    }

    /* ===== Sections ===== */
    main {
      max-width: 900px;
      margin: 4rem auto;
      padding: 0 1.5rem;
    }

    section {
      margin-bottom: 3rem;
      background-color: #1a1f25;
      border-radius: 10px;
      padding: 2.2rem;
      box-shadow: 0 0 25px rgba(0,0,0,0.45);
      transition: transform 0.3s ease;
    }

    section:hover {
      transform: scale(1.02);
    }

    h2 {
      border-left: 4px solid #1abc9c;
      padding-left: 0.6rem;
      font-size: 1.4rem;
      color: #1abc9c;
      font-family: 'Rajdhani', sans-serif;
      letter-spacing: 1px;
      margin-top: 0;
    }

    p {
      color: #ccc;
      margin-top: 1rem;
    }

    .photo {
      text-align: center;
      margin-top: 1.5rem;
    }

    .photo img {
      max-width: 100%;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(26,188,156,0.35);
    }

    /* ===== Footer ===== */
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #777;
      border-top: 1px solid #1abc9c;
      background-color: #0f1115;
      letter-spacing: 1px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Daichi</h1>
    <p>LEGO Creator / Fitness Enthusiast / Routine Lover</p>
  </header>

  <main>
    <section>
      <h2>PROFILE</h2>
      <p>2003年生まれ。LEGOブロックで育ち、今も創造することをやめない。筋トレとルーティンを通して、日々の成長と自己管理を楽しむ。構造の美と継続の力を信じる、静かな情熱家。</p>
    </section>

    <section>
      <h2>LEGO CREATIONS</h2>
      <p>作品は、日常の中から生まれるインスピレーション。無駄を削ぎ落としたデザインと機能美を追求し、ブロックで未来を形にする。創ること、それ自体が表現。</p>
      <div class="photo">
        <img src="daichi_legoland.jpg" alt="Daichi LEGO Land">
      </div>
    </section>

    <section>
      <h2>ROUTINE & MIND</h2>
      <p>朝は同じ時間に起き、筋トレと軽いストレッチで一日を始める。ルーティンを守ることで集中力と創造力を高め、安定したメンタルを保つ。静かに、しかし確実に積み上げていく。</p>
    </section>

    <section>
      <h2>VISION</h2>
      <p>LEGOのように、人生も組み立てていくもの。自由な発想で確かな形を創り、いつか「構築する力」で誰かを動かす存在に。</p>
    </section>
  </main>

  <footer>
    © 2025 Daichi Portfolio | Designed by Mom
  </footer>
</body>
</html>
