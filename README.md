<!-- README.md - Professional Data Scientist Profile (fixed) -->

<!-- ====== BANNER: put your image into the repo at assets/banner.png ====== -->
<p align="center">
  <!-- Use a local image inside your repo for consistent rendering -->
  <img src="./assets/banner.png" alt="Data science banner" style="max-width:100%; height:auto; border-radius:8px;" />
</p>

<h1 align="center">Shruti Somvanshi — Data Scientist</h1>
<p align="center">
  <a href="mailto:shruti.somvanshi@example.com">shruti.somvanshi@example.com</a> •
  <a href="https://www.linkedin.com/in/shruti-somvanshi/">LinkedIn</a> •
  <a href="https://github.com/your-github-username">GitHub</a>
</p>

---

## Summary
I build reproducible data science solutions: EDA, feature engineering, validated ML models, and dashboards for stakeholder-facing insights. I focus on clear communication, robust pipelines, and production-ready artifacts.

---

## Professional Snapshot
- **Core:** Python, Pandas, scikit-learn, TensorFlow/PyTorch, SQL  
- **Visualization:** Matplotlib, Seaborn, Plotly, Dash, Power BI  
- **Tools:** Jupyter, Git, Docker, CI, cloud inference (optional)

---

## Key Metrics (Edit these values below)
Below are placeholder values — open this file and replace the numbers (both the numeric labels and the percentage widths) with your real counts.

- Projects completed: **12**
- Public repos: **24**
- Analyses / reports: **30**
- Notebooks / demos: **18**

> To update: change the numbers in the SVG text nodes and the percentage widths of the bars. The bars use percent widths so they scale well.

<!-- ====== Bar chart (clean, high-contrast) ====== -->
<p align="center">
  <svg width="760" height="220" viewBox="0 0 760 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Portfolio metrics">
    <style>
      .title { font: 600 16px/1 'Inter', Arial, sans-serif; fill:#0f172a; }
      .label { font: 12px 'Inter', Arial, sans-serif; fill:#334155; }
      .value { font: 600 13px 'Inter', Arial, sans-serif; fill:#0f172a; }
      .bg { fill:#e6eef6; rx:8; }
      .bar { fill:#0369a1; rx:8; }
    </style>

    <text x="20" y="28" class="title">Portfolio Metrics</text>

    <!-- Row 1 -->
    <text x="20" y="70" class="label">Projects completed</text>
    <text x="700" y="70" text-anchor="end" class="value">12</text>
    <rect x="160" y="58" width="560" height="18" class="bg" />
    <!-- Replace width="50%" with your percentage for Projects (example 50%) -->
    <rect x="160" y="58" width="50%" height="18" class="bar" />

    <!-- Row 2 -->
    <text x="20" y="110" class="label">Public repositories</text>
    <text x="700" y="110" text-anchor="end" class="value">24</text>
    <rect x="160" y="98" width="560" height="18" class="bg" />
    <!-- Replace width="100%" with your percentage for Repos (example 100%) -->
    <rect x="160" y="98" width="100%" height="18" class="bar" />

    <!-- Row 3 -->
    <text x="20" y="150" class="label">Exploratory analyses / reports</text>
    <text x="700" y="150" text-anchor="end" class="value">30</text>
    <rect x="160" y="138" width="560" height="18" class="bg" />
    <!-- Replace width="80%" with your percentage for Analyses (example 80%) -->
    <rect x="160" y="138" width="80%" height="18" class="bar" />

    <!-- Row 4 -->
    <text x="20" y="190" class="label">Jupyter notebooks / demos</text>
    <text x="700" y="190" text-anchor="end" class="value">18</text>
    <rect x="160" y="178" width="560" height="18" class="bg" />
    <!-- Replace width="60%" with your percentage for Notebooks (example 60%) -->
    <rect x="160" y="178" width="60%" height="18" class="bar" />
  </svg>
</p>

**How to set correct widths quickly:** choose a baseline (for example, `public_repos` is max → `100%`), then compute each other metric as `(value / max) * 100` and paste that percentage into the `width="..."` attribute for each `.bar` rect.

---

## Language / Toolkit Distribution (Edit values)
Below is a static donut chart. Edit the legend percentages to reflect your real usage (and adjust colors if you want).

```svg
<!-- Copy this SVG block below the text to render the donut -->
<svg width="420" height="220" viewBox="0 0 420 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Language usage">
  <style>
    .title { font: 600 15px/1 'Inter', Arial, sans-serif; fill:#0f172a; }
    .legend { font: 12px 'Inter', Arial, sans-serif; fill:#334155; }
  </style>

  <text x="20" y="28" class="title">Language / Tool Usage</text>

  <!-- Donut center at (300,115) -->
  <g transform="translate(300,115)">
    <!-- Outer ring segments (static paths matching example percents). If you change percents, you can replace the paths or swap with an image -->
    <!-- Python 48% -->
    <path d="M 60 0 A 60 60 0 0 1 -9.6 58.4 L -9.6 58.4 A 36 36 0 0 0 35 0 Z" fill="#306998"/>
    <!-- C++ 16% -->
    <path d="M -9.6 58.4 A 60 60 0 0 1 -58.4 9.6 L -58.4 9.6 A 36 36 0 0 0 -5.6 9.6 Z" fill="#00599C"/>
    <!-- SQL 12% -->
    <path d="M -58.4 9.6 A 60 60 0 0 1 -35 -52 L -35 -52 A 36 36 0 0 0 -18 -39 Z" fill="#264de4"/>
    <!-- R 8% -->
    <path d="M -35 -52 A 60 60 0 0 1 35 -52 L 35 -52 A 36 36 0 0 0 20 -30 Z" fill="#276dc3"/>
    <!-- JS 16% -->
    <path d="M 35 -52 A 60 60 0 0 1 60 0 L 60 0 A 36 36 0 0 0 35 0 Z" fill="#f7df1e"/>
    <circle r="32" fill="#ffffff"/>
    <text x="0" y="6" font-size="11" text-anchor="middle" fill="#0f172a" font-weight="600">Usage</text>
  </g>

  <!-- Legend -->
  <g transform="translate(20,48)">
    <rect x="0" y="0" width="12" height="12" fill="#306998"/><text x="18" y="10" class="legend">Python — 48%</text>
    <rect x="0" y="24" width="12" height="12" fill="#00599C"/><text x="18" y="34" class="legend">C++ — 16%</text>
    <rect x="0" y="48" width="12" height="12" fill="#264de4"/><text x="18" y="58" class="legend">SQL — 12%</text>
    <rect x="0" y="72" width="12" height="12" fill="#276dc3"/><text x="18" y="82" class="legend">R — 8%</text>
    <rect x="0" y="96" width="12" height="12" fill="#f7df1e"/><text x="18" y="106" class="legend">JavaScript — 16%</text>
  </g>
</svg>
