<!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Paprika – YouTube csatorna</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg1:#7cc84b;
      --bg2:#6bb13f;
      --accent:#d9534f;
      --dark:#0b2b17;
      --card:#f3f3f3;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;font-family:Arial, Helvetica, sans-serif;background:linear-gradient(180deg,var(--bg1),var(--bg2));}
    .wrap{max-width:980px;margin:24px auto;padding:18px}

    header{background:linear-gradient(90deg,#2c5f2b,#1d3f1f);padding:18px;border:6px solid #111;box-shadow:8px 8px 0 rgba(0,0,0,0.25)}
    .title{display:flex;align-items:center;gap:18px}
    .logo{width:96px;height:96px;display:flex;align-items:center;justify-content:center;border:6px solid #000;background:linear-gradient(#ffd88a,#ffb347);box-shadow:4px 4px 0 rgba(0,0,0,0.25);font-family:'Press Start 2P',monospace;font-size:18px}
    h1{color:#fff;font-family:'Press Start 2P',monospace;font-size:20px;margin:0}
    p.tag{color:#dfeee0;margin:6px 0 0 0}

    nav{margin-top:14px;display:flex;gap:8px}
    .btn{display:inline-block;padding:10px 14px;border:4px solid #000;background:var(--accent);color:#fff;font-weight:700;text-decoration:none;font-family:'Press Start 2P',monospace;font-size:12px;box-shadow:6px 6px 0 rgba(0,0,0,0.25)}

    main{margin-top:18px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:18px}

    .card{background:var(--card);padding:14px;border:4px solid #000;box-shadow:6px 6px 0 rgba(0,0,0,0.15)}
    .about h2,.videos h2,.contact h2{font-family:'Press Start 2P',monospace;font-size:14px;margin:0 0 10px 0}
    .about p{margin:0 0 6px 0}

    .videos .thumbs{display:grid;grid-template-columns:1fr;gap:12px}
    .video-embed{border:4px solid #000}

    aside .box{position:sticky;top:18px}
    .socials a{display:block;margin-bottom:8px;padding:8px 10px;border:3px solid #000;background:#fff;text-decoration:none;color:#000;font-weight:700;font-family:'Press Start 2P',monospace;font-size:11px}

    footer{margin-top:20px;text-align:center;color:#07210d;font-weight:700;font-family:'Press Start 2P',monospace}

    @media (max-width:880px){.grid{grid-template-columns:1fr} .logo{width:72px;height:72px;font-size:12px}}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="title">
        <div class="logo">Paprika</div>
        <div>
          <h1>Paprika</h1>
          <p class="tag">YouTube csatorna • Minecraft stílus</p>
          <nav>
            <a class="btn" href="#videos">Videók</a>
            <a class="btn" href="#about">Rólam</a>
            <a class="btn" href="#contact">Kapcsolat</a>
          </nav>
        </div>
      </div>
    </header>

    <main class="grid">
      <section class="card videos" id="videos">
        <h2>Legújabb videók</h2>

        <div class="thumbs">
          <!-- Beágyazott YouTube videók -->
          <div class="video-embed">
            <iframe width="100%" height="220" src="https://www.youtube.com/embed/LdQeI9Usqfc" title="YouTube video" frameborder="0" allowfullscreen></iframe>
          </div>

          <div class="video-embed">
            <iframe width="100%" height="220" src="https://www.youtube.com/embed/R4aE6hgoKrc" title="YouTube video" frameborder="0" allowfullscreen></iframe>
          </div>

          <div class="video-embed">
            <iframe width="100%" height="220" src="https://www.youtube.com/embed/pSEaSbCcs64" title="YouTube video" frameborder="0" allowfullscreen></iframe>
          </div>
        </div>

      </section>

      <aside>
        <div class="box">
          <div class="card about" id="about">
            <h2>Rólam</h2>
            <p>Paprika vagyok, 13 éves.</p>
            <p>Kedvenc hobbim: foci és kosárlabda.</p>
          </div>

          <div class="card contact" id="contact" style="margin-top:12px">
            <h2>Kapcsolat</h2>
            <p>Email: <a href="mailto:banexx771@gmail.com">banexx771@gmail.com</a></p>
            <div class="socials" style="margin-top:8px">
              <a href="#">YouTube csatorna</a>
              <a href="#">Instagram</a>
            </div>
          </div>

          <div class="card" style="margin-top:12px;text-align:center">
            <p style="font-family:'Press Start 2P',monospace;font-size:11px;margin:0">Sablon</p>
            <p style="font-size:12px;margin:6px 0 0 0">Minecraft‑stílus theme</p>
          </div>
        </div>
      </aside>
    </main>

    <footer>
      © 2026 Paprika — YouTube csatorna oldal
    </footer>
  </div>
</body>
</html>
