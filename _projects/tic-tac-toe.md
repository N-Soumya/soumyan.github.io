---
layout: page
title: AI-Driven Misère Tic-Tac-Toe
---

# AI-Driven Misère Tic-Tac-Toe
[cite_start]**ASU Mobile Computing Project** [cite: 19]

[cite_start]A feature-rich Android application implementing the **Misère variant** of Tic-Tac-Toe, where the objective is inverted: the player who makes three in a row loses[cite: 18]. [cite_start]Built with **Kotlin**, **Jetpack Compose**, and modern Android architecture patterns[cite: 15].

---

## 🚀 Key Features
* [cite_start]**🤖 Intelligent AI Opponent**: Features three difficulty levels (Easy, Medium, and Hard)[cite: 21].
* [cite_start]**📡 Bluetooth P2P Multiplayer**: Connect and play with friends on separate devices via serverless Bluetooth communication[cite: 22].
* **📊 Persistent Game History**: A comprehensive history system using **Room Database** to track past games, outcomes, and difficulty levels.
* **⚙️ Dynamic Settings**: Seamlessly switch between game modes and difficulty levels mid-game without resetting the board.

---

## 🛠 Technical Implementation

### AI Engine (Minimax & Alpha-Beta Pruning)
[cite_start]Engineered an AI agent using the **Minimax algorithm with Alpha-Beta pruning** to achieve optimal gameplay[cite: 21].
* [cite_start]**Search Tree Complexity**: Optimized to manage mobile hardware resource constraints[cite: 21].
* **Misère Evaluation**: Unlike traditional Tic-Tac-Toe, the evaluation function is inverted (+10 for forcing an opponent's 3-in-a-row) to ensure the AI never loses in Hard mode.

### P2P Networking Layer
[cite_start]Implemented a robust peer-to-peer networking layer for device-to-device play[cite: 22].
* [cite_start]**Technology**: Utilized **Bluetooth Classic** for serverless connectivity[cite: 22].
* [cite_start]**Synchronization**: Developed custom **JSON protocols** for real-time game state synchronization and turn-based logic handling[cite: 22].

### Modern Android Architecture
* [cite_start]**Framework**: 100% **Kotlin** with **Jetpack Compose** for a declarative, reactive UI[cite: 13, 15].
* **Pattern**: Follows **MVVM (Model-View-ViewModel)** architecture to separate business logic from UI state.
* **Concurrency**: Leveraged **Kotlin Coroutines and Flow** for asynchronous operations, such as database queries and network messaging.

---

## 🛠 Technologies Used
* [cite_start]**Language**: Kotlin [cite: 13]
* [cite_start]**UI**: Jetpack Compose, Material 3 [cite: 15]
* **Architecture**: MVVM, Repository Pattern
* [cite_start]**Local Storage**: Room (SQLite) [cite: 15]
* [cite_start]**Networking**: Bluetooth Classic, Kotlin Serialization (JSON) [cite: 22]
* [cite_start]**Algorithms**: Minimax, Alpha-Beta Pruning [cite: 21]

---

## 📖 Game Rules
* The board is a 3×3 grid.
* Two players take turns placing their symbol (X or O).
* **The Loss Condition**: The player who makes three in a row (horizontally, vertically, or diagonally) **LOSES**.
