<!-- Retro Pixel GitHub README -->

<!-- Pixel Font -->
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Press Start 2P', monospace;
    background-color: #0d0d0d;
    color: #33ff33;
    animation: flicker 2s infinite;
  }

  @keyframes flicker {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.95; }
  }

  .about {
    animation: typing 4s steps(40, end), blink-caret 0.75s step-end infinite;
    white-space: nowrap;
    overflow: hidden;
    border-right: 3px solid #33ff33;
    width: 0;
  }

  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }

  @keyframes blink-caret {
    from, to { border-color: transparent; }
    50% { border-color: #33ff33; }
  }

  .section-title {
    font-size: 14px;
    margin: 20px 0 10px;
    text-transform: uppercase;
    color: #ff66cc;
  }

  .skill-list, .socials {
    list-style: none;
    padding-left: 0;
  }

  .skill-list li::before {
    content: "💾 ";
  }

  .socials a {
    text-decoration: none;
    color: #00ffff;
  }

  .socials a:hover {
    text-decoration: underline;
  }
</style>

<h1 align="center">🧠 Dusa Praharsh</h1>
<h3 align="center" style="color: #ffcc00;">🚀 Pixel Pioneer • Solidity Coder • Game Dev</h3>

<p class="about">
  A retro-loving builder who blends the past with the future. From crafting pixel-perfect games to deploying smart contracts, I live on the edge of code and creativity.
</p>

<h2 class="section-title">🧰 Digital Arsenal</h2>
<ul class="skill-list">
  <li>Three.js</li>
  <li>Unity</li>
  <li>Solidity</li>
  <li>React.js</li>
  <li>Next.js</li>
  <li>C#</li>
</ul>

<h2 class="section-title">📡 Transmission Lines</h2>
<ul class="socials">
  <li><a href="https://t.me/YOUR_TELEGRAM_USERNAME" target="_blank">📟 Telegram</a></li>
  <li><a href="https://twitter.com/DusaPraharsh" target="_blank">🛰️ Twitter</a></li>
  <li><a href="https://github.com/DusaPraharsh" target="_blank">🕹️ GitHub</a></li>
  <li><a href="https://www.linkedin.com/in/dusapraharsh/" target="_blank">📇 LinkedIn</a></li>
</ul>
