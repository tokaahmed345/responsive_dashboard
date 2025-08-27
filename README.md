<!DOCTYPE html>
<html lang="en">

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

