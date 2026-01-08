---
layout: page
title: Quantum ML for Hemodynamic Prediction
---

<style>
  /* Global Visibility Fix for Dark Theme */
  body {
    background-color: #000000 !important;
    color: #FFFFFF !important;
  }

  /* Typography */
  h1 { color: #bb86fc !important; border-bottom: 2px solid #30363d; padding-bottom: 10px; font-weight: 800 !important; }
  h2 { color: #a29bfe !important; margin-top: 30px; border-left: 5px solid #bb86fc; padding-left: 10px; font-weight: 800 !important; }
  h3 { color: #ffa657 !important; font-weight: 800 !important; }
  p, li, span, div { color: #FFFFFF !important; }
  strong, b { color: #FFFFFF !important; font-weight: 900 !important; }

  /* Buttons */
  .btn-nav {
    display: inline-block;
    padding: 8px 16px;
    background-color: #21262d;
    color: #bb86fc !important;
    text-decoration: none;
    border: 1px solid #30363d;
    border-radius: 5px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  .btn-nav:hover { border-color: #FFFFFF; }

  /* Skill Badges */
  .tech-badge {
    display: inline-block;
    background: #2d1b4e;
    color: #bb86fc !important;
    padding: 2px 10px;
    border-radius: 12px;
    font-size: 0.8em;
    margin-right: 5px;
    font-weight: bold;
    border: 1px solid #bb86fc;
    margin-bottom: 5px;
  }

  /* Box Styles */
  .highlight-box {
    background-color: #0d1117;
    border: 1px solid #30363d;
    border-left: 6px solid #bb86fc;
    padding: 15px;
    margin: 20px 0;
    border-radius: 4px;
  }
</style>

<a href="../../" class="btn-nav">← Back to Projects</a>

# Quantum ML & CFD Blood Flow Analysis
**Research Paper | KLE Technological University**

<div class="highlight-box">
Investigated the intersection of <strong>Quantum Computing</strong> and <strong>Medical Physics</strong> by comparing Quantum Machine Learning (QML) and classical ML in predicting blood flow dynamics within a 3D Aorta model.
</div>


<a href="https://github.com/N-Soumya/Blood-Flow-Analysis.git" target="_blank" style="
    display: inline-block;
    padding: 8px 16px;
    background-color: #238636;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
    margin-left: 10px;
    margin-bottom: 20px;
">View on Github</a>

---

## 🛠 Key Research Contributions
* **Quantum Circuit Engineering**: Developed variational quantum circuits using **Pennylane**, featuring ring-pattern **CNOT entanglement** for parameter interdependency mapping.
* **CFD Simulation**: Executed complex blood flow simulations on **Ansys Workbench**, utilizing the **Carreau rheological model** to capture non-Newtonian behavior.
* **High-Performance Execution**: Deployed QML jobs on **Amazon Braket** using the **SV1 State Vector Simulator** and **IonQ Aria 1** hardware.

---

## 🚀 Technical Implementation

### Aorta Modeling & Simulation
* **Geometry**: Modeled a human aorta with one inlet and four outlets based on anatomical averages.
* **Fluid Dynamics**: Applied the **PIMPLE algorithm** for stable pressure-velocity coupling in blood flow trajectories.
* **Data Volume**: Extracted and analyzed datasets from over **217,000 nodes** across 10 CSV extractions.

### Quantum vs. Classical Comparison
* **Classical Stack**: Implemented **Random Forest** and **Decision Tree** regressors achieving an MSE as low as **0.0105**.
* **Quantum Stack**: Utilized **X and Y rotations** for data encoding into qubits, followed by measurement of **Pauli-Z expectation values**.
* **Results**: QML circuits showed comparable logic handling to classical models, providing a foundation for scaling to hardware with higher qubit counts.

---

## 🏗 Tech Stack
<div style="margin: 10px 0;">
  <span class="tech-badge">Python</span>
  <span class="tech-badge">AWS Braket (SV1)</span>
  <span class="tech-badge">IonQ Aria 1</span>
  <span class="tech-badge">Pennylane</span>
  <span class="tech-badge">Ansys Workbench</span>
  <span class="tech-badge">CFD / Fluid Dynamics</span>
  <span class="tech-badge">Scikit-Learn</span>
</div>

---

[← Back to Project Tiles](../../)
