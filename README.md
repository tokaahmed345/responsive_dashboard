<!DOCTYPE html>
<html lang="en">
<head>
  <title>Responsive UI Dashboard — README</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Roboto, sans-serif;
      background: #f5f7fa;
      color: #333;
      line-height: 1.6;
      padding: 40px 20px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background: #fff;
      border-radius: 16px;
      padding: 30px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    }
    h1 {
      font-size: 32px;
      margin: 0 0 10px;
      color: #222;
    }
    .subtitle {
      color: #555;
      margin: 0 0 20px;
    }
    .kicker {
      font-size: 13px;
      display: inline-block;
      background: #eef3ff;
      color: #3b5bdb;
      padding: 4px 10px;
      border-radius: 999px;
      margin-bottom: 10px;
    }
    .badges {
      display: flex;
      gap: 8px;
      flex-wrap: wrap;
      margin-bottom: 20px;
    }
    .badge {
      font-size: 12px;
      background: #f0f0f0;
      color: #333;
      border-radius: 8px;
      padding: 6px 10px;
    }
    .grid {
      display: grid;
      gap: 20px;
      grid-template-columns: 1fr;
    }
    @media(min-width:800px){
      .grid {
        grid-template-columns: 1.2fr 0.8fr;
      }
    }
    h2 {
      font-size: 22px;
      margin: 20px 0 10px;
      color: #111;
    }
    ul {padding-left: 20px;}
    li {margin-bottom: 6px;}
    .code {
      background: #1e1e2f;
      color: #d0e6ff;
      padding: 14px;
      border-radius: 10px;
      font-family: monospace;
      font-size: 14px;
      overflow-x: auto;
    }
    .screens {
      display: grid;
      gap: 14px;
      grid-template-columns: repeat(1, 1fr);
      margin-top: 10px;
    }
    @media(min-width:600px){
      .screens {grid-template-columns: repeat(3, 1fr);}
    }
    .shot {
      border-radius: 12px;
      overflow: hidden;
      border: 1px solid #ddd;
      background: #fafafa;
    }
    .shot img {width: 100%; display: block;}
    .footer {
      margin-top: 20px;
      font-size: 13px;
      color: #666;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="kicker">Flutter • Responsive</div>
      <h1>Responsive UI Dashboard</h1>
      <p class="subtitle">A modern, responsive admin dashboard built with <span style="color:#3b5bdb;">Flutter</span>. Optimized for desktop, tablet, and mobile. This HTML file acts as a visual README for your project.</p>

      <div class="badges">
        <span class="badge">Flutter 3.5+</span>
        <span class="badge">Dart</span>
        <span class="badge">fl_chart</span>
        <span class="badge">flutter_svg</span>
      </div>

      <div class="grid">
        <div>
          <h2>✨ Features</h2>
          <ul>
            <li>Responsive layouts (desktop / tablet / mobile)</li>
            <li>Charts & analytics using <code>fl_chart</code></li>
            <li>SVG icons & illustrations with <code>flutter_svg</code></li>
            <li>Reusable widgets and clean architecture</li>
            <li>Device preview during development</li>
          </ul>

          <h2>▶️ Getting Started</h2>
          <p>Install dependencies and run the app:</p>
          <div class="code">
<pre>flutter pub get
flutter run</pre>
          </div>

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

        <div>
          <h2>🎨 UI Preview</h2>
          <div class="screens">
            <div class="shot"><img src="assets/images/desktop.png" alt="Desktop preview"></div>
            <div class="shot"><img src="assets/images/tablet.png" alt="Tablet preview"></div>
            <div class="shot"><img src="assets/images/mobile.png" alt="Mobile preview"></div>
          </div>
          <p class="footer">Place screenshots in <code>assets/images/</code> folder.</p>
        </div>
      </div>

      <h2>🧩 Packages</h2>
      <ul>
        <li><code>device_preview</code> — preview layouts on multiple devices</li>
        <li><code>expandable_page_view</code> — flexible page views</li>
        <li><code>fl_chart</code> — charts and graphs</li>
        <li><code>flutter_svg</code> — SVG assets support</li>
      </ul>

      <h2>📜 License</h2>
      <p>MIT — free for personal and commercial use.</p>
      <p>© <span id="year"></span> Your Name</p>
    </div>
  </div>

 
</body>
</html>

