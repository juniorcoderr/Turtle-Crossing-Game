# 🐢 Turtle Crossing Game – A Beginner-Friendly Python Project

Welcome to the **Turtle Crossing Game** – a classic arcade-style game built using Python's `turtle` graphics library. This project is designed to help **beginners** understand **Object-Oriented Programming (OOP)** and **game development basics** in Python — all while creating a fun and interactive game!

---

## 🎯 Game Concept

Your goal is to **guide the turtle across a busy road** filled with moving cars. Each time you successfully cross to the top, you level up and the cars get faster, increasing the challenge. But be careful — if a car hits the turtle, it’s **Game Over**!

---

## 🎮 Gameplay Overview

- Use the **Up Arrow key** to move the turtle forward.
- Dodge cars that come from the right side of the screen.
- Make it to the top to **increase your level**.
- The game becomes more difficult with each level as the **car speed increases**.
- The game ends when the turtle collides with a car.

---

## 🧠 What You Will Learn

This game is a great way to practice the following Python concepts:

### ✅ Python Basics
- Variables, conditionals, loops, and functions  
- Using built-in modules like `random` and `time`

### ✅ Object-Oriented Programming (OOP)
- Creating classes and objects  
- Inheritance (`Player` and `Scoreboard` inherit from `Turtle`)  
- Encapsulation and abstraction of game logic

### ✅ Turtle Graphics Module
- Drawing shapes and moving objects  
- Handling keyboard input and screen updates  
- Creating a simple UI with `write()`, `goto()`, etc.

### ✅ Game Development Logic
- Game loops  
- Collision detection  
- Object spawning and management  
- Level tracking and difficulty scaling

---

## 📁 Project Structure

```bash
turtle-crossing-game/
├── main.py           # Main file: game loop, object setup, event handling
├── player.py         # Player (turtle) class: movement, position, finish detection
├── car_manager.py    # CarManager class: spawns, moves, and speeds up cars
├── scoreboard.py     # Scoreboard class: handles level display and game over message
```

Each file is modular and easy to read, making it ideal for beginners to follow along.

---

## 🔧 How to Run the Game

### 1. Install Python (if not already installed)

You can download Python from [python.org](https://www.python.org/downloads/)

### 2. Clone or Download the Repository

```bash
git clone https://github.com/juniorcoderr/Turtle-Crossing-Game.git
cd turtle-crossing-game
```

Or simply download the ZIP and extract it.

### 3. Run the Game

```bash
python main.py
```

No external dependencies required — the game runs using **only built-in Python modules**.

---

## 💡 Tips for Beginners

- Try changing the **colors**, **car speed**, or **turtle shape** to customize the game.
- Modify the controls or add more features like lives, sound effects, or obstacles.
- Use this as a starting point to explore more advanced game libraries like `pygame`.

---

## 📌 Future Improvements (Optional Ideas)

- Add horizontal car lanes or different directions  
- Add lives or health system  
- Add sound effects using `pygame`  
- Save high scores  
- Add a main menu or restart option

---

## 🙌 Credits

Created as part of learning Python and understanding the fundamentals of game development using the `turtle` module.
