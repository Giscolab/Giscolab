<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Franck — Developer & Builder</title>

  <!-- Fonts (optionnel). Local-first ? supprime cette ligne et garde les fallbacks -->
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&family=JetBrains+Mono:wght@500;700&display=swap" rel="stylesheet">

  <style>
    :root{
      --primary:#2563eb; --accent:#0ea5e9;
      --bg1:#0b0e12; --bg2:#0f172a; --bg3:#1e293b; --card:#111827;
      --ink:#f8fafc; --ink2:#cbd5e1; --muted:#94a3b8; --line:#273244; --line2:#334155;
      --glow-a:#00E5FF; --glow-b:#7A5CFF; --glow-c:#FF2ED1;
      --radius:14px;
    }
    *{box-sizing:border-box;margin:0;padding:0}
    body{font-family:Inter,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Arial,sans-serif;background:linear-gradient(180deg,var(--bg1),var(--bg2));color:var(--ink);line-height:1.6}
    .container{max-width:1100px;margin:0 auto;padding:48px 24px}
    a{color:inherit;text-decoration:none}
    /* Header */
    .header{margin-bottom:40px}
    .title h1{font-family:"JetBrains Mono",Consolas,monospace;font-weight:700;letter-spacing:-.02em;font-size:3.25rem}
    .subtitle{color:var(--ink2);font-size:1.15rem}
    .tagline{font-family:"JetBrains Mono",Consolas,monospace;color:var(--accent);margin-top:8px;font-style:italic}
    .tags{display:flex;gap:10px;flex-wrap:wrap;margin-top:16px}
    .tag{background:linear-gradient(180deg,#0f141b,#0b0f16);border:1px solid var(--line2);padding:.5rem .9rem;border-radius:10px;color:#cfe3ff}
    /* Hero */
    .hero{margin:28px 0 36px;border:1px solid var(--line);border-radius:var(--radius);background:#0b0f16;position:relative;overflow:hidden}
    .hero::before{content:"";position:absolute;inset:-40%;background:radial-gradient(60% 60% at 20% 20%,rgba(0,229,255,.14),transparent 60%),radial-gradient(60% 60% at 80% 30%,rgba(122,92,255,.14),transparent 60%),radial-gradient(50% 50% at 50% 80%,rgba(255,46,209,.1),transparent 60%);filter:blur(20px)}
    .hero-inner{position:relative;padding:28px 28px}
    .badge{display:inline-flex;gap:8px;align-items:center;background:#0F141B;border:1px solid #1f2a37;border-radius:12px;padding:8px 12px;font-family:"JetBrains Mono",monospace;color:#DDE6F7}
    /* Sections */
    .section{margin:42px 0}
    .section-title{display:inline-block;font-weight:700;font-size:1.35rem;margin-bottom:16px;border-bottom:2px solid var(--primary);padding-bottom:6px}
    .card{background:linear-gradient(180deg,#0f141b,#0b0f16);border:1px solid var(--line2);border-radius:12px}
    .table{width:100%;border-collapse:collapse}
    .table th,.table td{padding:16px 20px;border-bottom:1px solid var(--line2)}
    .table th{width:160px;color:#e6efff;background:#0e1420;text-align:left}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px;margin-top:18px}
    .pill{background:#0F141B;border:1px solid #1f2a37;border-radius:10px;padding:12px;text-align:center;font-family:"JetBrains Mono",monospace;color:#dbeafe}
    .quote{margin:42px 0;padding:28px;text-align:center;border:1px solid var(--line2);border-radius:12px;background:linear-gradient(135deg,#121826,#0b1019)}
    .quote::after{content:"";display:block;height:2px;margin-top:16px;background:linear-gradient(90deg,var(--glow-a),var(--glow-b),var(--glow-c))}
    .contacts{display:flex;gap:14px;flex-wrap:wrap}
    .cta{display:inline-flex;align-items:center;gap:10px;background:#0e1420;border:1px solid var(--line2);border-radius:10px;padding:12px 16px}
    .cta:hover{border-color:#2d73ff}
    @media (max-width:768px){.title h1{font-size:2.4rem}}
  </style>
</head>
<body>
  <div class="container">
    <!-- Header -->
    <header class="header">
      <div class="title"><h1>Franck</h1></div>
      <p class="subtitle">Developer & Builder</p>
      <p class="tagline">« Build sharp. Keep it local. Ship clean. »</p>
      <div class="tags">
        <span class="tag">Local-first</span>
        <span class="tag">Crypto-minded</span>
        <span class="tag">Neumorphic UX</span>
      </div>
    </header>

    <!-- Hero (SVG glow inline) -->
    <section class="hero" aria-label="Hero visuel">
      <div class="hero-inner">
        <svg width="100%" height="120" viewBox="0 0 920 120" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="FRANCK">
          <defs>
            <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0%" stop-color="#00E5FF"/><stop offset="50%" stop-color="#7A5CFF"/><stop offset="100%" stop-color="#FF2ED1"/>
            </linearGradient>
            <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
              <feGaussianBlur stdDeviation="5" result="b"/>
              <feMerge><feMergeNode in="b"/><feMergeNode in="b"/></feMerge>
            </filter>
          </defs>
          <rect x="2" y="2" width="916" height="116" rx="12" fill="none" stroke="url(#g1)" filter="url(#glow)"/>
          <text x="20" y="76" font-family="JetBrains Mono,monospace" font-size="44" fill="url(#g1)">FRANCK</text>
          <text x="20" y="104" font-family="Inter,Arial" font-size="16" fill="#9fb3d1">Artist Developer — code, design & sound</text>
          <rect x="760" y="20" width="140" height="36" rx="10" fill="#0F141B" stroke="#1f2a37"/>
          <text x="775" y="43" font-family="JetBrains Mono,monospace" font-size="12" fill="#d8e7ff">local-first • PBKDF2</text>
        </svg>
      </div>
    </section>

    <!-- À propos -->
    <section class="section">
      <h2 class="section-title">À propos</h2>
      <div>
        <p>Ingénierie <strong>front-driven</strong>, sécurité pragmatique, performances mesurées.</p>
        <p>Je conçois des applications <strong>autonomes</strong> (<em>offline-ready</em>), avec des dépendances <strong>minimisées</strong> et une <strong>UX élégante & accessible</strong>.</p>
        <p>Approche artisanale : interfaces <strong>sensorielles</strong> (lumières, reliefs, rythmes) sans compromettre la maintenabilité technique.</p>
      </div>
    </section>

    <!-- Stack -->
    <section class="section">
      <h2 class="section-title">Stack & Approches</h2>
      <div class="card">
        <table class="table" role="table">
          <tr><th>Langages</th><td>TypeScript/JavaScript, Python, C#, HTML, CSS</td></tr>
          <tr><th>UI/3D</th><td>React (hooks explicites), R3F/Three.js</td></tr>
          <tr><th>Sécurité locale</th><td>IndexedDB + PBKDF2, <em>zero-cloud</em> par défaut</td></tr>
          <tr><th>Plateforme</th><td>Vite, pnpm, Git/GitHub, PowerShell</td></tr>
          <tr><th>Qualité</th><td>ESLint ciblé, tests de surface (Playwright), lisibilité & DX</td></tr>
          <tr><th>Design</th><td>Neumorphisme <strong>accessible</strong>, contrastes, focus states clairs</td></tr>
        </table>
      </div>
      <div class="grid">
        <div class="pill">TypeScript / React</div>
        <div class="pill">R3F / Three.js</div>
        <div class="pill">IndexedDB + PBKDF2</div>
        <div class="pill">Python</div>
        <div class="pill">C#</div>
        <div class="pill">Neumorphisme a11y</div>
      </div>
    </section>

    <!-- Mantra -->
    <section class="quote" aria-label="Mantra">
      <p><strong>Clair, local, maintenable.</strong> Chaque dépendance doit mériter sa place.</p>
    </section>

    <!-- Contact -->
    <section class="section">
      <h2 class="section-title">Contact</h2>
      <div class="card" style="padding:22px;">
        <div class="contacts">
          <a class="cta" href="LIEN_LINKEDIN"><span>💼</span> LinkedIn</a>
          <a class="cta" href="LIEN_PORTFOLIO"><span>🌐</span> Portfolio</a>
          <a class="cta" href="mailto:EMAIL"><span>📧</span> Email</a>
        </div>
      </div>
    </section>
  </div>
</body>
</html>
