# scrollx
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>ScrollX — Create Professional End Credits</title>
  <meta name="description" content="Create professional end credits in minutes. Templates, instant render, unlimited projects." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg1: #0f1724;
      --bg2: #071026;
      --accent: #7c6cff;
      --muted: #9aa4b2;
      --card: rgba(255,255,255,0.03);
      --glass: rgba(255,255,255,0.04);
      --radius: 14px;
      font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      color:#e6eef8;
      background: linear-gradient(180deg,var(--bg1),var(--bg2));
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
      line-height:1.45;
    }
    .container{max-width:1100px;margin:0 auto;padding:28px;}
    header{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
    .logo{display:flex;gap:12px;align-items:center}
    .logo .mark{
      width:46px;height:46px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#4dd0e1);
      display:flex;align-items:center;justify-content:center;font-weight:800;color:#041024;font-size:18px;
      box-shadow: 0 6px 20px rgba(124,108,255,0.18);
    }
    nav a{color:var(--muted);text-decoration:none;margin-left:18px;font-weight:500}
    .cta {display:flex; gap:10px; align-items:center}
    .btn {
      padding:10px 16px;border-radius:10px;border:1px solid rgba(255,255,255,0.06);
      background:transparent;color:inherit;text-decoration:none;font-weight:600;
    }
    .btn-primary{
      background: linear-gradient(90deg,var(--accent),#4dd0e1);
      color:#021224;border:none;box-shadow:0 8px 30px rgba(124,108,255,0.18);
    }

    /* HERO */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:36px 0}
    .eyebrow{display:inline-block;background:rgba(255,255,255,0.04);padding:6px 12px;border-radius:999px;color:#bcd3ff;font-weight:600;margin-bottom:12px}
    h1{font-size:36px;margin:6px 0 12px;line-height:1.05;color:white}
    p.lead{color:var(--muted);margin:0 0 20px}
    .features{display:flex;gap:12px;flex-wrap:wrap}
    .feature{background:var(--card);padding:12px;border-radius:10px;font-size:13px;color:var(--muted)}
    /* hero mockup */
    .mockup{
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(0,0,0,0.08));
      border-radius:16px;padding:18px;display:flex;flex-direction:column;gap:12px;align-items:center;justify-content:center;
      box-shadow: 0 12px 40px rgba(2,6,23,0.6);
      min-height:340px;
    }
    .screen{
      width:100%;height:220px;border-radius:10px;background:
      linear-gradient(180deg, rgba(3,7,18,0.9), rgba(6,10,24,0.85));
      border:1px solid rgba(255,255,255,0.03);display:flex;align-items:center;justify-content:center;color:var(--muted);
      font-weight:600;
    }

    /* FEATURES & PRICING */
    .section{padding:36px 0;border-top:1px solid rgba(255,255,255,0.02)}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
    .card{background:var(--glass);padding:18px;border-radius:12px}
    .price-cards{display:flex;gap:12px;flex-wrap:wrap}
    .price{flex:1;min-width:220px;padding:18px;border-radius:12px;background:linear-gradient(180deg, rgba(10,16,30,0.6), rgba(6,8,16,0.5));border:1px solid rgba(255,255,255,0.03)}
    .price h3{margin:0 0 8px}
    .muted{color:var(--muted)}

    footer{padding:28px 0;color:var(--muted);border-top:1px solid rgba(255,255,255,0.02);margin-top:18px;text-align:center}

    /* responsive */
    @media (max-width:960px){
      .hero{grid-template-columns:1fr;}
      .grid-3{grid-template-columns:1fr;}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">
        <div class="mark">SX</div>
        <div>
          <div style="font-weight:800">ScrollX</div>
          <div style="font-size:12px;color:var(--muted);margin-top:2px">End credits made simple</div>
        </div>
      </div>

      <nav>
        <a href="#features">Features</a>
        <a href="#pricing">Pricing</a>
        <a href="#blog">Blog</a>
        <span class="cta">
          <a class="btn" href="#">Log In</a>
          <a class="btn btn-primary" href="#">Join Free</a>
        </span>
      </nav>
    </header>

    <!-- HERO -->
    <section class="hero" aria-labelledby="hero-heading">
      <div>
        <div class="eyebrow">New</div>
        <h1 id="hero-heading">Professional End Credits<br><span style="color:var(--accent)">Made Simple</span></h1>
        <p class="lead">Perfectly formatted end credits ready in minutes. Pick a template, paste your credits, render an MP4 — done.</p>

        <div style="display:flex;gap:12px;margin-bottom:18px;">
          <a class="btn btn-primary" href="#">Join to Try for Free</a>
          <a class="btn" href="#">Watch Video</a>
        </div>

        <div class="features">
          <div class="feature">Templates — industry standard</div>
          <div class="feature">Real-time preview</div>
          <div class="feature">Export MP4 / High res</div>
        </div>
      </div>

      <aside class="mockup" aria-hidden="true">
        <div style="font-size:13px;color:var(--muted);font-weight:600">Preview</div>
        <div class="screen">[Video / Credits preview placeholder]</div>
        <div style="display:flex;gap:8px;width:100%;justify-content:space-between">
          <div style="font-size:13px;color:var(--muted)">720p • MP4</div>
          <div style="font-size:13px;color:var(--muted)">Watermarked (Free)</div>
        </div>
      </aside>
    </section>

    <!-- PROCESS -->
    <section id="features" class="section">
      <div style="display:flex;justify-content:space-between;align-items:center;gap:24px;flex-wrap:wrap">
        <div style="flex:1;min-width:260px">
          <h2 style="margin-top:0">Build End Credits in 3 Easy Steps</h2>
          <p class="muted">Enter credits, choose a template, and render. Fast—screening ready.</p>
        </div>
        <div style="flex:1;min-width:280px">
          <div class="grid-3">
            <div class="card">
              <strong>Step One</strong>
              <div class="muted" style="font-size:13px;margin-top:8px">Input cast & crew via our template</div>
            </div>
            <div class="card">
              <strong>Step Two</strong>
              <div class="muted" style="font-size:13px;margin-top:8px">Pick style & fonts</div>
            </div>
            <div class="card">
              <strong>Step Three</strong>
              <div class="muted" style="font-size:13px;margin-top:8px">Instant render — download MP4</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PRICING -->
    <section id="pricing" class="section">
      <h2 style="margin-top:0">Pricing</h2>
      <p class="muted">Choose the plan that fits your needs.</p>

      <div class="price-cards" style="margin-top:16px">
        <div class="price">
          <h3>Basic</h3>
          <div class="muted">Free • Watermarked • 720p</div>
          <p style="margin-top:12px;font-size:14px">Try ScrollX for free and explore powerful features.</p>
          <div style="margin-top:12px"><a class="btn" href="#">Get Started</a></div>
        </div>

        <div class="price">
          <h3>Essential</h3>
          <div class="muted">$99 / week</div>
          <p style="margin-top:12px;font-size:14px">Unlimited renders • High resolution • All formats</p>
          <div style="margin-top:12px"><a class="btn btn-primary" href="#">Choose Plan</a></div>
        </div>

        <div class="price">
          <h3>Pro</h3>
          <div class="muted">$199 / month</div>
          <p style="margin-top:12px;font-size:14px">Best for professionals & ongoing productions.</p>
          <div style="margin-top:12px"><a class="btn" href="#">Start Pro</a></div>
        </div>
      </div>
    </section>

    <footer>
      <div style="max-width:900px;margin:0 auto">
        <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
          <div style="text-align:left">
            <div style="font-weight:700">ScrollX</div>
            <div class="muted" style="font-size:13px">Create professional end credits — fast.</div>
          </div>
          <div class="muted" style="font-size:14px">Questions? Email <a href="mailto:hello@example.com" style="color:inherit;text-decoration:underline">hello@example.com</a></div>
        </div>

        <div style="margin-top:16px;font-size:13px;color:var(--muted)">© <span id="year"></span> All rights reserved.</div>
      </div>
    </footer>
  </div>

  <script>
    // small nicety
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
