<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Responsive UI Dashboard — README</title>
  <style>
    :root{
      --bg:#0f1220;
      --card:#171a2a;
      --muted:#a7b0c0;
      --text:#e9eef7;
      --accent:#7c9cff;
      --accent2:#22d3ee;
      --code:#0b0f1a;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, "Helvetica Neue", Arial;
      background: radial-gradient(1200px 600px at 10% -10%, rgba(124,156,255,.15), transparent 60%),
                  radial-gradient(1200px 600px at 110% 10%, rgba(34,211,238,.15), transparent 60%),
                  var(--bg);
      color:var(--text);
      line-height:1.6;
      padding:48px 20px;
    }
    .container{max-width:1100px;margin:0 auto}
    .card{
      background:linear-gradient(180deg, rgba(255,255,255,.04), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.08);
      border-radius:20px;
      padding:28px;
      box-shadow: 0 20px 40px rgba(0,0,0,.25);
      backdrop-filter: blur(6px);
    }
    h1{font-size: clamp(28px, 4vw, 40px);margin:0 0 12px;}
    .subtitle{color:var(--muted);margin:0 0 22px;}
    .badges{display:flex;gap:10px;flex-wrap:wrap;margin:14px 0 6px}
    .badge{
      font-size:12px;
      background:linear-gradient(180deg, rgba(124,156,255,.18), rgba(124,156,255,.08));
      color:#dfe7ff;border:1px solid rgba(124,156,255,.35);
      border-radius:999px;padding:6px 10px
    }
    .grid{display:grid;gap:20px;grid-template-columns: 1fr}
    @media(min-width:860px){.grid{grid-template-columns: 1.2fr .8fr}}
    .section{margin-top:28px}
    h2{font-size: clamp(20px, 3vw, 28px);margin:0 0 8px}
    p{margin:0 0 10px;color:#d8dfeb}
    ul{margin:10px 0 0 18px;color:#d8dfeb}
    li{margin:6px 0}
    .code{
      background:var(--code);
      border:1px solid rgba(255,255,255,.08);
      border-radius:14px;
      padding:14px;
      font-family: monospace;
      font-size: 13px;
      color:#cfe5ff;
    }
    .screens{display:grid;gap:14px;grid-template-columns: repeat(1, 1fr);margin-top:10px}
    @media(min-width:720px){.screens{grid-template-columns: repeat(3, 1fr)}}
    .shot{border-radius:16px;overflow:hidden;border:1px solid rgba(255,255,255,.08);background:var(--card);}
    .shot img{display:block;width:100%;height:auto}
    .footer{margin-top:30px;color:var(--muted);font-size:14px}
    .accent{color:var(--accent2)}
    a{color:var(--accent)}
    .kicker{
      display:inline-block;
      font-size:12px;
      color:#bcd3ff;
      background:linear-gradient(180deg, rgba(124,156,255,.12), rgba(124,156,255,.04));
      border:1px solid rgba(124,156,255,.25);
      padding:4px 8px;border-radius:999px;margin-bottom:10px
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="kicker">Flutter • Responsive</div>
      <h1>Responsive UI Dashboard</h1>
      <p class="subtitle">A modern, responsive admin dashboard built with <span class="accent">Flutter</span>. Optimized for desktop, tablet, and mobile. This HTML file acts as a visual README for your project.</p>

      <div class="badges">
        <span class="badge">Flutter 3.5+</span>
        <span class="badge">Dart</span>
        <span class="badge">fl_chart</span>
        <span class="badge">flutter_svg</span>
      </div>

      <div class="grid section">
        <div>
          <h2>✨ Features</h2>
          <ul>
            <li>Responsive layouts (desktop / tablet / mobile)</li>
            <li>Charts & analytics using <code>fl_chart</code></li>
            <li>SVG icons & illustrations with <code>flutter_svg</code></li>
            <li>Reusable widgets and clean architecture</li>
            <li>Device preview during development</li>
          </ul>

          <div class="section">
            <h2>▶️ Getting Started</h2>
            <p>Install dependencies and run the app:</p>
            <div class="code">
<pre>flutter pub get
flutter run</pre>
            </div>
          </div>

          <div class="section">
            <h2>📂 Structure</h2>
            <div class="code">
<pre>lib/
├─ main.dart
├─ responsive/        # breakpoints & layout helpers
├─ utils/             # themes, constants, generated assets
├─ widgets/           # reusable UI components
└─ screens/           # dashboard pages</pre>
            </div>
          </div>
        </div>

        <div>
          <h2>🎨 UI Preview</h2>
          <div class="screens">
            <div class="shot"><img src="assets/images/desktop.png" alt="Desktop dashboard preview"></div>
            <div class="shot"><img src="assets/images/tablet.png" alt="Tablet dashboard preview"></div>
            <div class="shot"><img src="assets/images/mobile.png" alt="Mobile dashboard preview"></div>
          </div>
          <p class="footer">Place screenshots in <code>assets/images/</code> folder.</p>
        </div>
      </div>

      <div class="section">
        <h2>🧩 Packages</h2>
        <ul>
          <li><code>device_preview</code> — preview layouts on multiple devices</li>
          <li><code>expandable_page_view</code> — flexible page views</li>
          <li><code>fl_chart</code> — charts and graphs</li>
          <li><code>flutter_svg</code> — SVG assets support</li>
        </ul>
      </div>

      <div class="section">
        <h2>📜 License</h2>
        <p>MIT — free for personal and commercial use.</p>
        <p>© <span id="year"></span> Your Name</p>
      </div>
    </div>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>

