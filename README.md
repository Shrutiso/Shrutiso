
<!-- README.md (copy this whole file) -->

<!-- ===== Banner: put your image at ./assets/banner.png ===== -->
<p align="center">
  <img src="./assets/banner.png" alt="Data Science Banner" style="max-width:100%; height:auto; border-radius:8px;" />
</p>

<h1 align="center">Shruti Somvanshi — Data Scientist</h1>
<p align="center">
  <a href="mailto:shruti.somvanshi@example.com">shruti.somvanshi@example.com</a> •
  <a href="https://www.linkedin.com/in/shruti-somvanshi/">LinkedIn</a> •
  <a href="https://github.com/your-github-username">GitHub</a>
</p>

---

## Quick summary
I build reproducible data science solutions: exploratory analysis, validated ML models, and dashboards. Below are portfolio metrics and a language/tool distribution chart.

---

<!-- ====== METRICS - update numbers below to your real counts ====== -->
<!-- Replace the numbers in the "DATA" block below; widths already computed for these example values -->
<!-- Example data used: projects=12, repos=24, analyses=30, notebooks=18 -->

<!--
  If you change these numbers:
   - set max_value = max(of your values)
   - bar_px = Math.round((value / max_value) * 560)
   - then replace the width="XXX" values below with calculated bar_px
-->

## Portfolio metrics
<p align="center">
  <!-- SVG bar chart: widths are pixels (safe rendering on GitHub) -->
  <svg width="760" height="220" viewBox="0 0 760 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Portfolio metrics">
    <!-- Title -->
    <text x="20" y="28" font-family="Arial" font-weight="600" font-size="16" fill="#0f172a">Portfolio Metrics</text>

    <!-- Row 1: Projects completed -->
    <text x="20" y="70" font-family="Arial" font-size="12" fill="#334155">Projects completed</text>
    <text x="700" y="70" text-anchor="end" font-family="Arial" font-weight="600" font-size="13" fill="#0f172a">12</text>
    <rect x="160" y="58" width="560" height="18" fill="#eef6fb" rx="8" />
    <!-- computed width = 224 px (12/30*560) -->
    <rect x="160" y="58" width="224" height="18" fill="#0369a1" rx="8" />

    <!-- Row 2: Public repositories -->
    <text x="20" y="110" font-family="Arial" font-size="12" fill="#334155">Public repositories</text>
    <text x="700" y="110" text-anchor="end" font-family="Arial" font-weight="600" font-size="13" fill="#0f172a">24</text>
    <rect x="160" y="98" width="560" height="18" fill="#eef6fb" rx="8" />
    <!-- computed width = 448 px (24/30*560) -->
    <rect x="160" y="98" width="448" height="18" fill="#0369a1" rx="8" />

    <!-- Row 3: Analyses / reports -->
    <text x="20" y="150" font-family="Arial" font-size="12" fill="#334155">Exploratory analyses / reports</text>
    <text x="700" y="150" text-anchor="end" font-family="Arial" font-weight="600" font-size="13" fill="#0f172a">30</text>
    <rect x="160" y="138" width="560" height="18" fill="#eef6fb" rx="8" />
    <!-- computed width = 560 px (30/30*560) -->
    <rect x="160" y="138" width="560" height="18" fill="#0369a1" rx="8" />

    <!-- Row 4: Notebooks -->
    <text x="20" y="190" font-family="Arial" font-size="12" fill="#334155">Jupyter notebooks / demos</text>
    <text x="700" y="190" text-anchor="end" font-family="Arial" font-weight="600" font-size="13" fill="#0f172a">18</text>
    <rect x="160" y="178" width="560" height="18" fill="#eef6fb" rx="8" />
    <!-- computed width = 336 px (18/30*560) -->
    <rect x="160" y="178" width="336" height="18" fill="#0369a1" rx="8" />
  </svg>
</p>

---

## Language / Tool usage
Below donut shows example usage breakdown. Example percentages: Python 48%, C++ 16%, SQL 12%, R 8%, JS 16%.

> If you want the donut to reflect your exact percentages, tell me your percentages or replace the numbers in the `stroke-dasharray`/`stroke-dashoffset` values (I can compute them for you).

<p align="center">
  <!-- Donut chart built using stroke-dasharray (works well on GitHub) -->
  <svg width="420" height="220" viewBox="0 0 420 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Language usage">
    <text x="20" y="28" font-family="Arial" font-weight="600" font-size="15" fill="#0f172a">Language / Tool Usage</text>

    <!-- Donut center at (300,115), radius 60 -->
    <!-- circumference = ~377 -->
    <!-- Segments (example): Python 48% -> 181, C++ 16% -> 60, SQL 12% -> 45, R 8% -> 30, JS 16% -> 60 -->
    <!-- We draw slices as multiple circles with different stroke-dasharray and offsets -->

    <g transform="translate(300,115) rotate(-90)">
      <!-- background ring -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#eef2ff" stroke-width="28" />
      <!-- Python slice -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#306998" stroke-width="28"
              stroke-dasharray="181 377" stroke-dashoffset="0" stroke-linecap="butt" />
      <!-- C++ slice -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#00599C" stroke-width="28"
              stroke-dasharray="60 377" stroke-dashoffset="-181" stroke-linecap="butt" />
      <!-- SQL slice -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#264de4" stroke-width="28"
              stroke-dasharray="45 377" stroke-dashoffset="-241" stroke-linecap="butt" />
      <!-- R slice -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#276dc3" stroke-width="28"
              stroke-dasharray="30 377" stroke-dashoffset="-286" stroke-linecap="butt" />
      <!-- JS slice -->
      <circle r="60" cx="0" cy="0" fill="none" stroke="#f7df1e" stroke-width="28"
              stroke-dasharray="60 377" stroke-dashoffset="-316" stroke-linecap="butt" />
      <!-- inner circle (hole) -->
      <circle r="36" cx="0" cy="0" fill="#ffffff" stroke="none" />
      <text x="0" y="6" font-family="Arial" font-size="11" text-anchor="middle" fill="#0f172a" font-weight="600">Usage</text>
    </g>

    <!-- Legend -->
    <g transform="translate(20,48)">
      <rect x="0" y="0" width="12" height="12" fill="#306998"/><text x="18" y="10" font-family="Arial" font-size="12" fill="#334155">Python — 48%</text>
      <rect x="0" y="24" width="12" height="12" fill="#00599C"/><text x="18" y="34" font-family="Arial" font-size="12" fill="#334155">C++ — 16%</text>
      <rect x="0" y="48" width="12" height="12" fill="#264de4"/><text x="18" y="58" font-family="Arial" font-size="12" fill="#334155">SQL — 12%</text>
      <rect x="0" y="72" width="12" height="12" fill="#276dc3"/><text x="18" y="82" font-family="Arial" font-size="12" fill="#334155">R — 8%</text>
      <rect x="0" y="96" width="12" height="12" fill="#f7df1e"/><text x="18" y="106" font-family="Arial" font-size="12" fill="#334155">JavaScript — 16%</text>
    </g>
  </svg>
</p>


