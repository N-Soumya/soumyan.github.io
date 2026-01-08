---
layout: page
title: High-Performance Accident Pattern Analysis Platform
---

<style>
  h1 { color: #2c3e50; border-bottom: 2px solid #27ae60; padding-bottom: 10px; }
  h2 { color: #2ecc71; margin-top: 30px; border-left: 5px solid #27ae60; padding-left: 10px; }
  h3 { color: #2980b9; }
  .tech-badge {
    display: inline-block;
    background: #27ae60;
    color: white;
    padding: 2px 10px;
    border-radius: 12px;
    font-size: 0.8em;
    margin-right: 5px;
    font-weight: bold;
    margin-bottom: 5px;
  }
  .contribution-box {
    background-color: #f4fdf4;
    border-left: 6px solid #2ecc71;
    padding: 15px;
    margin: 20px 0;
    border-radius: 4px;
  }
  .viz-box {
    background-color: #f0f7ff;
    border-left: 6px solid #3498db;
    padding: 15px;
    margin: 20px 0;
    border-radius: 4px;
  }
</style>

<a href="../../" style="
    display: inline-block;
    padding: 8px 16px;
    background-color: #0366d6;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    margin-bottom: 20px;
">← Back to Projects</a>

# High-Performance Accident Pattern Analysis Platform
**ASU Data Visualization Project** 

<div class="contribution-box">
This platform delivers a data-driven narrative of traffic accident trends in Montgomery County, Maryland, using interactive storytelling and high-performance geospatial analysis.
</div>

---

## 🛠 My Key Contribution: Mosaic Chart Analysis
I engineered the **Mosaic Chart** visualization using the **Photino D3 Components Library** to uncover deep correlations between environmental factors and accident outcomes.

* **Feature Logic**: Analyzed the complex relationship between **lighting conditions** (dawn, dusk, daylight, etc.) and **injury severity**.
* **Technical Impact**: Connected poor lighting conditions during dawn and dusk to significantly higher injury rates.
* **UX Design**: Integrated a customized color scheme and interactive features that allow users to identify risk trends across different lighting environments.

---

## 🚀 Advanced Technical Implementation

### Geospatial Optimization & Indexing
To handle large-scale transportation datasets efficiently, I focused on high-performance backend and geospatial logic:
* **Spatial Indexing**: Integrated **RBush** for spatial indexing, enabling high-speed searches across thousands of geographic accident locations.
* **Geospatial Computation**: Utilized **Turf.js** for advanced spatial analysis, including distance calculations and hotspot identification.
* **Query Performance**: Optimized geospatial queries and data structures to maintain a seamless user experience even with large datasets.

### Full-Stack Tech Stack
<div style="margin: 10px 0;">
  <span class="tech-badge">JavaScript (ES6+)</span>
  <span class="tech-badge">D3.js</span>
  <span class="tech-badge">Node.js</span>
  <span class="tech-badge">Express</span>
  <span class="tech-badge">RBush</span>
  <span class="tech-badge">Turf.js</span>
  <span class="tech-badge">jQuery</span>
  <span class="tech-badge">GitHub Pages</span>
</div>

* **Frontend**: JavaScript, HTML5/CSS3, **D3.js** for custom visualizations, and jQuery for enhanced interactivity.
* **Data Processing**: Leveraged **Node.js** and **Express** for server-side processing.
* **Data Transformation**: Utilized `csvtojson` and `json-2-csv` for efficient data cleaning and transformation.
* **Hosting**: Deployed via **GitHub Pages** for public accessibility.

---

## 📊 Platform Visualizations
<div class="viz-box">
Beyond the Mosaic Chart, the platform integrates:
<ul>
  <li><strong>Car-in-a-Clock Chart</strong>: An innovative visualization mapping collision impact directions onto a clock face combined with a spider chart for severity comparison.</li>
  <li><strong>Geo-Spatial Map</strong>: Built with GIS software to pinpoint high-risk zones and targeted safety intervention areas.</li>
  <li><strong>TreeMap & Stacked Bar Charts</strong>: Hierarchical blocks and comparative bars revealing risks associated with driver error and adverse weather.</li>
</ul>
</div>

---

[← Back to Project Tiles](../../)
