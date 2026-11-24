# 🧪 Smart Mathematics Laboratory (Lower Secondary Edition)

An interactive, web-based **Smart Mathematics Laboratory** designed specifically for lower secondary students (**Grades 7–9**). This platform bridges the gap between abstract mathematical concepts and visual, hands-on experimentation through interactive simulations, dynamic geometry, probability models, and STEAM-integrated learning modules.

---

## 🎯 Overview & Vision

Traditional mathematics instruction often relies on static diagrams and rote memorization. The **Smart Mathematics Laboratory** transforms the classroom into an exploratory environment where students can manipulate variables in real time, observe mathematical patterns, and build intuition across algebra, geometry, statistics, and probability.

### Key Objectives
* **Visual & Experiential Learning:** Turn abstract equations and geometric theorems into tangible, interactive experiments.
* **STEAM Integration:** Connect mathematical principles with science, engineering, coding, and real-world problem-solving.
* **Classroom & Projector Ready:** Designed with high-contrast, light-mode interfaces optimized for smart boards, illuminated classrooms, and mobile/tablet browsers.
* **Self-Paced Exploration:** Enable students to test hypotheses, make mistakes, and discover rules independently.

---

## ✨ Core Modules & Features

### 1. 📐 Interactive Geometry & Measurement
* **Coordinate Plane & Line Slope Explorer:** Dynamically adjust slope ($m$) and y-intercept ($b$) to observe real-time changes in linear equations ($y = mx + b$).
* **Pythagorean Theorem & Right Triangles:** Visual proofs and interactive side-length manipulation.
* **Transformations & Symmetry:** Explore translations, rotations, reflections, and congruence on an interactive grid.
* **3D Shapes & Volume:** Unfold 3D nets (prisms, cylinders, pyramids, cones) to connect surface area with volume formulas.

### 2. 🔢 Algebra & Algebraic Identities
* **Virtual Algebra Tiles:** Visual representation of polynomials, factoring, and algebraic identities such as $(a + b)^2 = a^2 + 2ab + b^2$ and $(a - b)(a + b) = a^2 - b^2$.
* **Equation Balance Scale:** Solve linear equations step by step using an interactive balance model.
* **Exponents & Powers Visualizer:** Understand exponential growth and exponent laws through area and volume models.

### 3. 🎲 Probability & Statistics Simulator
* **Galton Board (Quincunx) Simulation:** Drop marbles through a peg board to observe how random events converge into a normal distribution.
* **Coin Toss & Dice Roll Experiments:** Run single trials or thousands of automated simulations to compare experimental probability with theoretical probability.
* **Data & Graph Builder:** Input datasets to generate histograms, bar charts, pie charts, and calculate mean, median, mode, and range.

### 4. 🛠️ STEAM & Hardware Integration
* Companion digital tools and data visualizers designed to pair with physical classroom kits (e.g., sensor-based algebra boards, physical Galton boards, and microcontroller experiments).

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Responsive Grid/Flexbox), Vanilla JavaScript (ES6+)
* **Graphics & Visualization:** HTML5 Canvas API / SVG / Chart.js
* **Typography & Math Rendering:** MathJax / KaTeX for crisp mathematical notation
* **Architecture:** Lightweight, zero-dependency static web architecture (runs smoothly offline or via GitHub Pages)

---

## 📂 Project Structure

```text
smart-math-lab/
├── index.html              # Main landing page & module selector
├── assets/
│   ├── css/
│   │   └── style.css       # High-contrast classroom-friendly themes
│   ├── js/
│   │   └── main.js         # Core navigation & shared utilities
│   └── images/             # Diagrams, icons, and visual assets
├── modules/
│   ├── algebra-tiles/      # Interactive algebraic identities simulator
│   ├── line-slope/         # Linear equations & coordinate grid lab
│   ├── galton-board/       # Probability & normal distribution simulator
│   └── geometry-3d/        # 3D nets and volume explorer
├── docs/                   # Teacher guides & student worksheets
├── LICENSE                 # Open-source license
└── README.md               # Project documentation
