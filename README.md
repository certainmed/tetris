# Pastel Tetris

A modern, aesthetically pleasing implementation of the classic Tetris game, built entirely with **Vanilla JavaScript (ES6+)** and **HTML5 Canvas**. This project focuses on clean Object-Oriented architecture, high performance, and a responsive pastel design without any external dependencies.

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Language](https://img.shields.io/badge/javascript-ES6%2B-yellow.svg)

## ✨ Key Features

* **Modern Aesthetic:** Features a soothing pastel color palette managed via CSS variables with a 3D "soft plastic" visual style.
* **Responsive Design:** The game board and UI dynamically scale to fit various screen sizes (from 400px to large desktop displays) using CSS media queries.
* **Fair Gameplay:** Implements the **7-Bag Randomizer system**, ensuring players receive a balanced distribution of tetrominoes (no long droughts of specific pieces).
* **Performance Optimized:** Utilizing a smart rendering system that only repaints "dirty" (changed) areas of the canvas, ensuring a smooth 60 FPS experience.
* **Progressive Difficulty:** Drop speed increases dynamically as players clear rows.
* **Dependency-Free:** Runs purely in the browser with no build steps, frameworks, or external libraries required.

## 🎮 Controls

The game is designed for desktop keyboard input:

| Key | Action |
| :--- | :--- |
| **Space** | Start Game / Restart |
| **Esc** | End Game |
| **↑** (Up Arrow) | Rotate Piece |
| **↓** (Down Arrow) | Soft Drop |
| **← / →** | Move Left / Right |

## 🚀 Getting Started

### Prerequisites
You only need a modern web browser (Chrome, Firefox, Safari, or Edge) to run this game.

### Installation & Running
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/certainmed/tetris.git](https://github.com/certainmed/tetris.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd tetris
    ```
3.  **Play the game:**
    Simply open the `index.html` file in your preferred web browser.

## 📂 Project Structure

```text
pastel-tetris/
├── index.html      # The core entry point containing HTML, CSS, and Game Logic
└── stats.js        # A refactored performance monitor (Optional developer tool)
