# Math Quiz Console Game (C++)

## 📌 Project Overview

This project is a **console-based Math Quiz game** developed in **C++**. The game challenges the player with a series of arithmetic questions based on a selected difficulty level and operation type. At the end of the quiz, the program evaluates the player's performance and displays detailed results.

The project is designed to practice core C++ concepts such as enums, structs, functions, control flow, and random number generation.

---

## 🎯 Game Features

* Choose the number of questions
* Select difficulty level:

  * Easy
  * Medium
  * Hard
  * Mixed
* Select operation type:

  * Addition
  * Subtraction
  * Multiplication
  * Division
  * Mixed operations
* Randomly generated math questions
* Instant feedback for each answer
* Console color feedback for correct and incorrect answers
* Final performance summary (Pass / Fail / Equal)
* Option to replay the game

---

## 🛠️ Technologies Used

* **Language:** C++
* **Libraries:**

  * `<iostream>` for input/output
  * `<string>` for string handling
  * `<cstdlib>` for random numbers and system commands

---

## 📂 Project Structure

```
MathQuizGame/
│── MathQuiz.cpp
│── README.md
```

---

## ▶️ How to Run the Game

1. Make sure you have a C++ compiler installed (e.g. **g++**).
2. Compile the program:

   ```bash
   g++ MathQuiz.cpp -o MathQuiz
   ```
3. Run the executable:

   ```bash
   ./MathQuiz
   ```

   *(On Windows, run `MathQuiz.exe`)*

---

## 🧠 Game Logic Summary

* Questions are generated randomly based on the selected level
* If **Mixed** mode is selected, operations or difficulty levels are randomized
* Correct and incorrect answers are counted during gameplay
* Final result is determined by comparing correct vs incorrect answers

---

## 🚀 Future Improvements

* Prevent negative results for subtraction (optional)
* Floating-point division support
* Timer-based questions
* Score saving and statistics
* Graphical User Interface (GUI)

---

## 👤 Author

Ahmed Ali Kamal
Computer Science Student | Backend & AI Enthusiast

## 📄 License

This project is licensed for educational use.

All rights reserved © 2025 Ahmed Ali Kamal.
