# 2048 Game – Java Implementation

🚀 **Project:** 2048 Game Logic  
🧠 **Language:** Java  
🎯 **Focus:** Object-Oriented Design, Game State Management, Unit Testing

---

## 📌 Overview

This project implements the core logic of the popular single-player puzzle game **2048** in Java. While the graphical interface and game scaffolding were provided, the main challenge was to design and implement the **core game engine** — specifically, how tiles move, merge, and when the game ends.

The project also provided experience in working within a large, unfamiliar codebase — a real-world scenario where reading, testing, and debugging are just as important as writing code.

---

## 🎮 Game Mechanics

The game is played on a 4×4 grid, where tiles combine when pushed in the same direction. The goal is to reach a tile with the number **2048**, but the game can continue as long as there are valid moves.

---

## 💡 Implemented Features

Key game functionality was implemented in the `Model.java` file, including:

| Method | Description |
|--------|-------------|
| `emptySpaceExists(Board b)` | Detects if any empty tiles are on the board |
| `maxTileExists(Board b)` | Checks if the winning tile (2048) is present |
| `atLeastOneMoveExists(Board b)` | Determines whether any valid moves remain |
| `tilt(Side s)` | Governs tile movement, merging, and score updates per directional move |

These methods handle game logic including tile movement, merging behavior, scoring, and game-over conditions.

---

## 🧪 Testing

The game logic was validated using a comprehensive test suite, including:

- ✅ Unit tests for logic functions
- 🔄 Integration tests simulating gameplay
- 🔁 Directional behavior tests (Up, Down, Left, Right)

All game mechanics were debugged using structured tests and visual inspection of game state.

---

## ⚙️ Technologies Used

- Java 17
- IntelliJ IDEA
- JUnit 4
- Git & GitHub

---

## 🧭 Key Takeaways

- Designing modular and maintainable object-oriented systems
- Managing complex conditional logic (tile merges, valid moves, edge cases)
- Debugging large Java projects using automated testing
- Writing efficient code that interacts with dynamic UI-driven systems

---



