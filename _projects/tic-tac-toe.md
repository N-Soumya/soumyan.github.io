---
layout: page
title: AI-Driven Misère Tic-Tac-Toe
---

<style>
  h1 { color: #2c3e50; border-bottom: 2px solid #3498db; padding-bottom: 10px; }
  h2 { color: #2980b9; margin-top: 30px; border-left: 5px solid #3498db; padding-left: 10px; }
  h3 { color: #d35400; }
  .tech-badge {
    display: inline-block;
    background: #3498db;
    color: white;
    padding: 2px 10px;
    border-radius: 12px;
    font-size: 0.8em;
    margin-right: 5px;
    font-weight: bold;
  }
  .highlight-box {
    background-color: #f7f9fc;
    border-left: 6px solid #3498db;
    padding: 15px;
    margin: 20px 0;
    border-radius: 4px;
  }
  .rules-box {
    background-color: #fff4e5;
    border-left: 6px solid #e67e22;
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

# AI-Driven Misère Tic-Tac-Toe
**ASU Mobile Computing Project** 
<div class="highlight-box">
  A feature-rich Android application implementing the <strong>Misère variant</strong> of Tic-Tac-Toe, where the objective is inverted: the player who makes three in a row loses. Built with <strong>Kotlin</strong>, <strong>Jetpack Compose</strong>, and modern Android architecture patterns.
</div>

---

## 🚀 Key Features
* **🤖 Intelligent AI Opponent**: Features three difficulty levels: Easy, Medium, and Hard.
* **📡 Bluetooth P2P Multiplayer**: Connect and play via serverless Bluetooth communication.
* **📊 Persistent Game History**: Uses **Room Database** to track past games and outcomes.
* **⚙️ Dynamic Settings**: Seamlessly switch modes and difficulty levels mid-game.

---

## 🛠 Technical Implementation

### AI Engine (Minimax & Alpha-Beta Pruning)
Engineered an AI agent using the **Minimax algorithm with Alpha-Beta pruning** for optimal gameplay.
* **Search Tree Complexity**: Optimized to manage mobile hardware resource constraints.
* **Misère Evaluation**: Inverted evaluation (+10 for forcing opponent's 3-in-a-row) ensures the AI never loses in Hard mode.

### P2P Networking Layer
Implemented a robust peer-to-peer networking layer for device-to-device play.
* **Technology**: Utilized **Bluetooth Classic** for serverless connectivity.
* **Synchronization**: Developed custom **JSON protocols** for real-time state synchronization.

### Modern Android Architecture
* **Framework**: 100% **Kotlin** with **Jetpack Compose**.
* **Pattern**: Follows **MVVM** architecture to separate logic from UI state.
* **Concurrency**: Leveraged **Kotlin Coroutines and Flow** for reactive data streams.

---

## 🏗 Technologies Used
<div style="margin-top: 10px;">
  <span class="tech-badge">Kotlin</span>
  <span class="tech-badge">Jetpack Compose</span>
  <span class="tech-badge">Room DB</span>
  <span class="tech-badge">Coroutines</span>
  <span class="tech-badge">Bluetooth P2P</span>
  <span class="tech-badge">Minimax</span>
</div>

---

## 📖 Game Rules
<div class="rules-box">
  <ul>
    <li>The board is a 3×3 grid.</li>
    <li>Two players take turns placing their symbol (X or O).</li>
    <li><strong>The Loss Condition</strong>: The player who makes three in a row (horizontally, vertically, or diagonally) <strong>LOSES</strong>.</li>
  </ul>
</div>

[← Back to Project Tiles](../../)
