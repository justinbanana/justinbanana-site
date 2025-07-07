<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Just_in_Banana 🍌</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Comic+Neue:wght@700&display=swap');
    body {
      margin:0; padding:0;
      font-family:'Comic Neue', cursive, sans-serif;
      background:#fefefe; color:#333;
      text-align:center;
    }
    /* Hero */
    .hero {
      background:#ffeb3b url('hero-bg.jpg') center/cover no-repeat;
      padding:80px 20px;
      position:relative;
    }
    .hero::after {
      content:""; position:absolute;
      top:0; left:0; width:100%; height:100%;
      background:rgba(255,255,255,0.6);
    }
    .hero-content{
      position:relative; z-index:1;
    }
    .hero h1 {
      font-size:4rem; margin:0;
      color:#6e3480;
      text-shadow:2px 2px #fff;
    }
    .hero p {
      font-size:1.2rem; margin:20px 0;
      color:#462e00;
    }
    .btn {
      display:inline-block;
      margin:10px 15px;
      padding:15px 30px;
      font-size:1.3rem; font-weight:700;
      color:#3a2e00;
      background:#f1c40f;
      border:4px solid #b38600;
      border-radius:50px;
      text-decoration:none;
      box-shadow:0 0 15px rgba(241,196,15,0.7);
      transition:transform 0.3s, background 0.3s;
    }
    .btn:hover {
      transform:scale(1.08);
      background:#f7d94c;
    }
    .section {
      padding:60px 20px;
      max-width:800px;
      margin:0 auto;
    }
    .section h2 {
      color:#8e44ad;
      font-size:2.5rem;
      text-shadow:1px 1px #fff;
    }
    .section p {
      font-size:1.1rem;
      line-height:1.6;
      margin-top:15px;
      color:#5a4500;
    }
    footer {
      background:#333; color:#eee;
      padding:20px;
      font-size:0.9rem;
    }
    .social a {
      display:inline-block;
      margin:0 10px;
    }
    .social svg {
      width:30px; height:30px;
      fill:#fff;
      transition:fill 0.3s;
    }
    .social a:hover svg {
      fill:#1DA1F2;
    }
  </style>
</head>
<body>

  <!-- HERO SECTION -->
  <section class="hero">
    <div class="hero-content">
      <h1>JUST_IN_BANANA /we trust/</h1>
      <p>no pump and dump • hype and bite • meme coin</p>
      <a class="btn" href="#buy">🍌 Buy Now (SUUNN)!</a>
      <a class="btn" href="#buy">Trade on DEX (SUUNN)</a>
    </div>
  </section>

  <!-- ABOUT -->
  <section class="section" id="about">
    <h2>What is Just_in_Banana?</h2>
    <p>
      Just_in_Banana is the next-gen meme coin with all the 🍌 energy.
      Built for fun, community, and meme stonks.
      Bounce into the peel revolution where laughs & gains come together!
    </p>
  </section>

  <!-- BUY CTA -->
  <section class="section" id="buy">
    <h2>Get Your Bananas</h2>
    <p>
      Simply connect your wallet and swap on popular DEXes.
      Banana power coming very suunn!
    </p>
    <a class="btn" href="https://example-dex.com/just_in_banana">Connect Wallet (SUUNN)</a>
  </section>

  <!-- SOCIAL -->
  <section class="section social">
    <a href="https://x.com/Banana_ART" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" aria-hidden="true">
        <path d="M23.643 4.937c-.835...z"/>
      </svg>
    </a>
    <!-- add Telegram, Discord icons here -->
  </section>

  <footer>
    © 2025 Just_in_Banana • peel responsibly 🍌
  </footer>

</body>
</html>
