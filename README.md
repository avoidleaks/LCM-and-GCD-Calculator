# 🧮 LCM & GCD Calculator (Euclidean Algorithm)

An interactive, responsive web application built to calculate the **Greatest Common Divisor (GCD)** and **Least Common Multiple (LCM)** while visualizing every division transformation step using the Euclidean Algorithm[cite: 4].

---

## ✨ Features

* **Step-by-Step Euclidean Algorithm Visualizer:** Displays every division step ($a = q \times b + r$) with remainder highlighting and animated step progression[cite: 4].
* **Dual Computation:** Automatically calculates both GCD and LCM upon input[cite: 4].
* **BigInt Overflow Protection:** Uses JavaScript `BigInt` fallbacks for precise computations with very large integers[cite: 4].
* **Modern Glassmorphism UI:** Clean visual design with adaptive dark/light gradients, smooth slide animations, and full mobile responsiveness[cite: 4].
* **Keyboard-Friendly:** Supports immediate evaluation using the `Enter` key and dynamic form clearing[cite: 4].

---

## 📐 Mathematical Logic

1. **Euclidean Algorithm (GCD):**
   $$a = q \cdot b + r$$
   The algorithm continuously replaces $(a, b)$ with $(b, r)$ until $r = 0$, revealing the final non-zero value as the Greatest Common Divisor[cite: 4].
   * **Time Complexity:** $O(\log(\min(a, b)))$

2. **Least Common Multiple (LCM):**
   Evaluated using the relationship between product and GCD:
   $$\text{LCM}(a, b) = \frac{|a \times b|}{\text{GCD}(a, b)}$$[cite: 4]

---

## 🛠️ Tech Stack

* **HTML5:** Semantic markup with accessibility (`aria`) attributes[cite: 4].
* **CSS3:** Custom styles utilizing CSS Grid, Flexbox, backdrop filters, and keyframe animations[cite: 4].
* **JavaScript (Vanilla ES6):** Native DOM manipulation and modular arithmetic logic without external dependencies[cite: 4].

---

## 📜 License
This project is licensed under the **GNU General Public License v3.0**.
