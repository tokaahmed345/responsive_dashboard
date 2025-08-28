<!DOCTYPE html>
<html lang="en">
<head>
 
  <style>
    body {
      font-family: "Segoe UI", Roboto, sans-serif;
      background: #f7f9fc;
      color: #333;
      line-height: 1.6;
      padding: 20px 40px;
    }
    h1, h2 {
      color: #2b2d42;
    }
    pre {
      background: #1e1e2f;
      color: #d0e6ff;
      padding: 12px;
      border-radius: 6px;
      overflow-x: auto;
    }
    img {
      border-radius: 8px;
      border: 1px solid #ddd;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    .screens {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin: 20px 0;
    }
    .screens img {
      width: 300px;
    }
    ul {margin-left: 20px;}
    .contact a { color: #3b5bdb; text-decoration: none; }
  </style>
</head>
<body>

<h1>📊 Responsive UI Dashboard</h1>

<p>
Responsive Admin Dashboard built with <strong>Flutter</strong>, designed to work seamlessly on desktop 🖥️, tablet 📱, and mobile 📲.  
This README showcases features, screenshots, and project setup.
</p>

<hr>

<h2>📸 Screenshots</h2>
<div class="screens">
  <div>
    <h3>🖥️ Desktop</h3>
    <img src="screenshots/desktop.png" alt="Desktop preview">
  </div>
  <div>
    <h3>📱 Tablet</h3>
    <img src="screenshots/tablet.png" alt="Tablet preview">
  </div>
  <div>
    <h3>📲 Mobile</h3>
    <img src="screenshots/mobile.png" alt="Mobile preview">
  </div>
</div>

<hr>

<h2>✨ Features</h2>
<ul>
  <li>Responsive layouts for all devices</li>
  <li>Beautiful dashboard UI with charts and analytics</li>
  <li>Navigation drawer and app bar design</li>
  <li>Clean and reusable Flutter widgets</li>
  <li>Supports dark/light themes</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li><strong>Flutter</strong> 3.x</li>
  <li><strong>Dart</strong></li>
  <li><strong>fl_chart</strong> for charts</li>
  <li><strong>flutter_svg</strong> for icons</li>
  <li><strong>Provider / Cubit</strong> for state management</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>
<pre>
lib/
├── main.dart
├── responsive/        # layout helpers & breakpoints
├── utils/             # colors, themes, constants
├── widgets/           # reusable UI components
└── screens/           # dashboard pages
</pre>

<hr>

<h2>🚀 Getting Started</h2>
<ol>
  <li>Clone the repo:
    <pre>git clone https://github.com/yourusername/responsive_dashboard.git</pre>
  </li>
  <li>Install dependencies:
    <pre>flutter pub get</pre>
  </li>
  <li>Run the app:
    <pre>flutter run</pre>
  </li>
</ol>

<hr>

<h2>📊 Dashboard Demo</h2>
<p>Example chart integration using <code>fl_chart</code>:</p>
<img src="screenshots/chart.png" alt="Chart preview" width="500">

<hr>

<h2>📧 Contact</h2>
<p class="contact">
Made with ❤️ by <strong>Your Name</strong><br>
<a href="https://github.com/yourusername">GitHub</a> |
<a href="mailto:yourmail@example.com">Email</a>
</p>

</body>
</html>


