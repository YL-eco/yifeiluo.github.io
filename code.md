---
layout: default
title: Code
permalink: /code
---

{% include nav.html %}

# Code & Software

<div class="card">
  <h3>💻 Research Software</h3>
  <p>
    I maintain research code and small utilities supporting my work in political economy and economic history. 
    Below are selected projects with links to repositories, replication packages, and brief notes.
  </p>
</div>

<div class="code-item">
  <h4>stable-lasso-iv</h4>
  <p><em>Robust instrument & control selection for econometric analysis</em></p>
  <p>
    Automates sample-split Lasso for IV and control selection; outputs selection frequencies, final model, and LaTeX tables.
  </p>
  <div class="code-links">
    <a href="#">📦 Repository (Coming Soon)</a>
    <a href="#">📊 Replication Package (Coming Soon)</a>
    <a href="#">📋 Documentation (Coming Soon)</a>
  </div>
  
  <details>
    <summary><em>🔧 Usage Notes</em></summary>
    <div>
      <p>
        Batch Lasso for instruments and controls with stability selection; exports selection frequencies and a final IV model. 
        Includes helpers for clustered SEs and FE. Suitable for moderately large datasets. Written in Python with pandas, 
        numpy, and scikit-learn dependencies.
      </p>
    </div>
  </details>
</div>

<div class="code-item">
  <h4>Spatial RI with Placebo Outcome Variables</h4>
  <p><em>Modified inference for IV settings with spatial persistence</em></p>
  <p>
    Modifies inference in IV settings to account for spatial persistence using placebo outcomes and randomization inference.
  </p>
  <div class="code-links">
    <a href="#">📦 Repository (Coming Soon)</a>
    <a href="#">📊 Replication Package (Coming Soon)</a>
    <a href="#">📋 Documentation (Coming Soon)</a>
  </div>
  
  <details>
    <summary><em>🔧 Usage Notes</em></summary>
    <div>
      <p>
        Provides placebo-outcome generators over spatial grids and randomization inference routines compatible with clustered 
        settings; designed to plug into standard IV pipelines. Includes visualization tools for spatial autocorrelation 
        diagnostics and Monte Carlo simulation capabilities.
      </p>
    </div>
  </details>
</div>

<div class="card">
  <h3>🛠️ Technical Skills</h3>
  <ul class="clean">
    <li>
      <strong>Programming Languages</strong><br>
      Python (pandas, numpy, scikit-learn, matplotlib, seaborn), R, Stata, MATLAB
    </li>
    <li>
      <strong>Data Analysis</strong><br>
      Econometric modeling, spatial analysis, machine learning, data visualization
    </li>
    <li>
      <strong>Tools & Platforms</strong><br>
      Git, LaTeX, Jupyter notebooks, Docker, cloud computing platforms
    </li>
    <li>
      <strong>Specialized Software</strong><br>
      ArcGIS, QGIS, Stata, R Studio, Python IDEs
    </li>
  </ul>
</div>

<div class="card">
  <h3>📊 Data Sources & Methods</h3>
  <p>
    My research often involves working with diverse data sources and developing custom analysis pipelines:
  </p>
  <ul class="clean">
    <li><strong>Historical Data</strong> — Archival records, census data, trade statistics</li>
    <li><strong>Geographic Data</strong> — GIS datasets, spatial boundaries, coordinate systems</li>
    <li><strong>Survey Data</strong> — Public opinion polls, demographic surveys</li>
    <li><strong>Administrative Data</strong> — Government records, institutional databases</li>
  </ul>
</div>

<div class="card">
  <h3>🔗 Open Source Contributions</h3>
  <p>
    I believe in the importance of open science and reproducible research. All my research code will be made 
    publicly available with proper documentation and replication materials.
  </p>
  <div class="contact-links">
    <a href="https://github.com/yifeiluo">💻 GitHub Profile</a>
    <a href="#">📦 Research Repositories (Coming Soon)</a>
  </div>
</div>



