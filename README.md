# Conway-s_Game_of_life_Simulation_using_python-B3-S23
# 🧬 Conway's Game of Life (B3/S23)

Welcome to my implementation of **Conway's Game of Life**! 🚀

If you've never heard of it, the Game of Life is not a typical "game." It is a **cellular automaton** invented by British mathematician John Horton Conway in 1970. It is a "zero-player game," meaning its evolution is determined entirely by its initial state, requiring no further input from human players. 

You simply create an initial configuration (a pattern of "alive" cells) and watch how it evolves and creates complex, fascinating patterns over time based on a few simple mathematical rules.

---

## 📜 The Rules: B3/S23

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square *cells*, each of which is in one of two possible states: **Alive** or **Dead**. Every cell interacts with its eight neighbors (horizontal, vertical, and diagonal).

This specific implementation follows the standard **B3/S23** rule set, which stands for **B**orn on 3, **S**urvives on 2 or 3:

1. **Underpopulation:** Any live cell with fewer than two live neighbors dies.
2. **Survival (S23):** Any live cell with exactly two or three live neighbors lives on to the next generation.
3. **Overpopulation:** Any live cell with more than three live neighbors dies.
4. **Reproduction/Birth (B3):** Any dead cell with exactly three live neighbors becomes a live cell.

All these births and deaths happen simultaneously in a single moment, called a **tick** or **generation**.

---

## ⚙️ Why is this interesting?

Despite having only four simple rules, the Game of Life is completely unpredictable. It can generate:
* **Still Lifes:** Patterns that never change.
* **Oscillators:** Patterns that repeat themselves after a certain number of generations.
* **Spaceships (like the famous Glider):** Patterns that travel across the grid.

In fact, the Game of Life is **Turing Complete**, meaning that (theoretically) it can simulate any computer algorithm!

---

## 💻 Technologies Used
* **[Python]**


---
