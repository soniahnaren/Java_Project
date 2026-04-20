# 🤖 Smart AI Guessing Game (Java)

## 📌 Project Overview

The **Smart AI Guessing Game** is an advanced console-based Java application where the player guesses a randomly generated number with the help of intelligent hints.
Unlike traditional guessing games, this version introduces **adaptive difficulty, smart hinting, and a scoring system**, making it more engaging and interactive.

---

## 🚀 Features

### 🎯 Core Gameplay

* Random number generation
* Multiple attempts per level
* Level-based progression

### 🧠 Smart Hint System

* ❄️ Cold → far from number
* 🌡️ Warm → getting closer
* 🔥 Very Hot → very close to number
* 📈 / 📉 Direction hints (higher/lower)

### 🏆 Scoring System

* Points awarded based on attempts
* Bonus for faster guessing
* 🔥 Combo bonus for consecutive wins

### 📊 Advanced Mechanics

* Dynamic difficulty (range increases with level)
* Score scaling per level
* Replay system

---

## 🛠️ Technologies Used

* Java
* OOP Concepts (basic structure)
* Random class (number generation)
* Scanner (user input)

---

## 📂 Project Structure

```id="r2z8mx"
SmartAIGuessGame.java
```

---

## ▶️ How to Run

### Step 1: Compile the program

```id="k6m1pq"
javac SmartAIGuessGame.java
```

### Step 2: Run the program

```id="x8c3jd"
java SmartAIGuessGame
```

---

## 🧪 Sample Input

```id="n7w2qf"
20
45
40
38
yes
```

---

## 📤 Sample Output

```id="b9t5xr"
Level 1 | Range: 1 - 70

Guess: 20
❄️ Cold
📉 Go Higher

Guess: 45
🌡️ Warm
📈 Go Lower

Guess: 40
🔥 VERY HOT!
📈 Go Lower

Guess: 38
🎯 Correct!
🔥 Combo x1 Bonus: +20

🏆 Total Score: 120
```

---

## 🔍 Concepts Covered

* Random number generation
* Conditional logic and loops
* Input validation
* Game design logic
* State management (level, score, combo)

---

## 🚀 Future Enhancements

* 🖥️ GUI version using Java Swing/JavaFX
* 📊 Leaderboard system
* 💾 Save scores using file handling
* 🎵 Sound effects and animations
* 🤖 AI-based guessing pattern analysis

---

## 👨‍💻 Author

* Name: [Your Name]
* Course: Java Programming

---

## 📄 License

This project is developed for educational purposes only.
