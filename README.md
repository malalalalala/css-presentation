<h1>CSS Presentation</h1>
<p>
  Interactive presentation covering CSS fundamentals with <strong>Reveal.js</strong>.
  Perfect for newcomers who want to grasp syntax, the cascade, and best‑practice
  organisation of styles.
</p>

## Table of Contents

1. **Syntax & Definitions** – Basic anatomy of a CSS rule
2. **Box Model & Display** – Block vs. inline elements, margins, borders, padding
3. **Selectors & Specificity** – Element, class, ID, compounding, and the cascade
4. **The Cascade** – Order, specificity, and the dreaded `!important`
5. **Placing CSS** – External style‑sheets, internal `<style>`, inline styles
6. **Semantic CSS / Naming** – Why meaningful class names matter
7. **Pre‑processors** – Sass, Less, Stylus, PostCSS & their killer features
8. **Live‑Coding Demos** – Box‑model inspection, responsive units, overrides
9. **Things to Google Next** – Pseudo‑elements, `calc()`, Flexbox, Grid, etc.

<h2>Project layout</h2>
<pre><code>.
├── index.html          Main presentation file
├── css/                Reveal themes &amp; custom styles
├── js/                 Reveal.js library
├── lib/                Extra deps (highlight.js, html5shiv…)
├── images/             Graphics used in the slides
└── README.html         This document
</code></pre>

<h2>Run locally</h2>
<ol>
  <li><strong>Clone</strong> the repo:<br>
    <code>git clone https://github.com/your‑user/css‑crash‑course.git</code></li>
  <li><strong>Enter</strong> the folder:<br>
    <code>cd css‑crash‑course</code></li>
  <li><strong>Start</strong> a static server (pick one):<br>
    <ul>
      <li>Python 3:<br><code>python -m http.server 8282</code></li>
      <li>Node + http‑server:<br><code>npm i -g http-server && http-server -p 8282</code></li>
    </ul>
  </li>
  <li>Visit <code>http://localhost:8282/index.html</code> and navigate with the arrow keys.</li>
</ol>

<h2>Export to PDF</h2>
<p>
  Append <code>?print-pdf</code> to the URL:<br>
  <code>http://localhost:8282/index.html?print-pdf</code><br>
  then use <em>Print → Save as PDF</em>. Reveal.js auto‑loads the print stylesheet.
</p>

<h2>Quick customisation</h2>
<table>
  <tr><td><strong>Colour theme</strong></td><td><code>css/simple.css</code> or swap the theme link in <code>index.html</code></td></tr>
  <tr><td><strong>Your own styles</strong></td><td><code>css/custom.css</code></td></tr>
  <tr><td><strong>Plugins / transitions</strong></td><td>Block <code>Reveal.initialize</code> in <code>index.html</code></td></tr>
  <tr><td><strong>Images &amp; GIFs</strong></td><td><code>images/</code> folder</td></tr>
  <tr><td><strong>Slide content</strong></td><td><code>&lt;section&gt;</code> elements in <code>index.html</code></td></tr>
</table>

<h2>Main dependencies</h2>
<ul>
  <li><strong>Reveal.js</strong> — HTML slide engine (MIT)</li>
  <li><strong>highlight.js</strong> — Code syntax highlighting (BSD‑3)</li>
  <li><strong>html5shiv</strong> — HTML5 support for IE &lt; 9 (MIT)</li>
</ul>

<h2>Authors</h2>
<ul>
  <li>Original presentation: <strong>Jessica Keener</strong></li>
  <li>Spanish adaptation &amp; notes: <strong>Laura Ramos</strong> – laura.ramos@udea.edu.co</li>
</ul>

<h2>Licence</h2>
<p>
  Released under the <strong>MIT Licence</strong>.  
  Feel free to use, modify and share as long as you keep this notice.
</p>

<hr>
<p style="text-align:center">Enjoy learning CSS! For questions or suggestions, open an issue or drop an email.</p>

</body>
</html>
