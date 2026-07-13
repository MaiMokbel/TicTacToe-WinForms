### ❌⭕ Tic-Tac-Toe – Windows Forms Desktop Game

### 📖 Overview

Tic-Tac-Toe is a desktop application developed in **C#** using **Windows Forms** that recreates the classic two-player strategy game with a clean graphical user interface.

The application allows two players to compete on a 3×3 game board while automatically detecting winning combinations, tracking player scores, and providing an intuitive interface for starting new games.

Designed with simplicity and responsiveness in mind, the project demonstrates event-driven programming, object-oriented design, and GUI development using the .NET Framework.

---

### ✨ Features

- 🎮 Two-player gameplay (Player X vs Player O)
- 🖥 Interactive Windows Forms graphical interface
- ✔ Automatic turn switching
- 🏆 Automatic winner detection
- 📊 Live score tracking
- 🔄 Start a new game without restarting the application
- 🚫 Prevents additional moves after a winner is declared
- 🚪 Exit button to close the application
- 💬 Winner notification using message boxes

---

### 🛠 Technologies Used

- C#
- Windows Forms (WinForms)
- .NET Framework
- Visual Studio
- Object-Oriented Programming (OOP)

---

#### 📂 Project Structure

```
TicTacToe/
│
├── Form1.cs
├── Form1.Designer.cs
├── Program.cs
├── App.config
├── Properties/
└── README.md
```

---

### 🎮 Game Rules

- Player **X** always starts first.
- Players take turns selecting an empty square.
- The first player to align **three identical symbols** horizontally, vertically, or diagonally wins.
- After a winner is determined, the board is disabled until a new game is started.
- The winner's score is automatically updated.

---

### ⚙️ How It Works

The application follows an event-driven design.

1. The game starts with an empty 3×3 board.
2. Each button represents one cell of the board.
3. Clicking a cell places either **X** or **O** depending on the current turn.
4. After every move, the program checks all possible winning combinations.
5. If a winner exists:
   - A message is displayed.
   - The winner's score is increased.
   - The board is disabled.
6. Selecting **New Game** clears the board while preserving the scores.

---

### 🏗 Object-Oriented Concepts

This project demonstrates several core programming concepts, including:

- Event-Driven Programming
- Object-Oriented Programming (OOP)
- Methods and Functions
- Conditional Logic
- Loops
- State Management
- GUI Programming
- Button Event Handling

---

### 📸 Screenshots

### Main Game Window

<img width="543" height="641" alt="image" src="https://github.com/user-attachments/assets/5c907cd9-d1de-4518-ada8-d5253552923d" />

---

### Gameplay

<img width="528" height="645" alt="image" src="https://github.com/user-attachments/assets/4e9f3745-26a9-436e-a5df-9012a92acd5f" />


---

### Winning Screen

<img width="527" height="647" alt="image" src="https://github.com/user-attachments/assets/5566d85b-1f5f-4895-92c6-fa59642a7ee9" />

---

### Score Tracking

<img width="520" height="623" alt="image" src="https://github.com/user-attachments/assets/411d2691-e87f-4481-8452-12058440b6d3" />

---

## 🚀 How to Run

### Requirements

- Visual Studio
- .NET Framework
- Windows Operating System


---

### 📋 Features Implemented

- ✅ Two-player mode
- ✅ Graphical User Interface
- ✅ Winner Detection
- ✅ Row validation
- ✅ Column validation
- ✅ Diagonal validation
- ✅ Score Counter
- ✅ New Game
- ✅ Exit Application
- ✅ Winner Notification

---

### 📚 Concepts Demonstrated

- C# Programming
- Windows Forms Development
- Event Handling
- Object-Oriented Programming
- Desktop Application Development
- Game Logic Implementation
- User Interface Design

---

### 📈 Future Improvements

Possible enhancements include:

- 🎨 Dark mode and custom themes
- 🎵 Sound effects
- ✨ Winning line animation
- 🌐 Online multiplayer
- 📱 Responsive interface
---
