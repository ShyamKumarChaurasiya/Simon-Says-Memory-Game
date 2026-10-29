# 🎮 Simon Says – Memory Game

A classic color-based memory game built using **HTML5, CSS3, and JavaScript**. Challenge your memory by remembering and repeating an increasingly long sequence of flashing colored buttons.

🔗 **GitHub Repository:** https://github.com/ShyamKumarChaurasiya/Simon-Says-Memory-Game

---

## 📌 About the Project

Simon Says is an interactive browser-based memory game inspired by the classic Simon electronic game.

The game generates a random sequence of colors. The player must observe the sequence and repeat it by clicking the corresponding colored buttons in the correct order.

With every successful round, the game progresses to the next level and adds another color to the sequence. A wrong selection ends the game and displays the player's score.

This project was developed to strengthen my understanding of JavaScript fundamentals, DOM manipulation, event handling, and interactive web development.

## ✨ Features

- 🎨 Four interactive colored buttons:
  - Yellow
  - Red
  - Purple
  - Green
- 🎲 Random color sequence generation
- ⌨️ Keyboard-based game start
- 💡 Flash animations for game sequences
- 🖱️ Interactive button click effects
- 📈 Automatic level progression
- 🧠 Sequence matching and validation
- 🏆 Score calculation based on the achieved level
- 🔴 Game-over visual feedback
- 🔄 Restart functionality after game over

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Game structure and content |
| CSS3 | Styling, layout, colors, and animations |
| JavaScript | Game logic, sequence generation, and user interaction |
| DOM Manipulation | Updating game state and visual elements |
| Event Listeners | Handling keyboard and button interactions |
| `setTimeout()` | Managing animation timing and level progression |

## 🎮 How to Play

1. Open the game in your browser.
2. Press any key to start.
3. Watch the colored button that flashes.
4. Click the same colored button.
5. Remember the sequence as the game progresses.
6. Repeat the complete sequence in the correct order.
7. Each successful round advances you to the next level.
8. If you click the wrong button, the game ends.
9. Your score is displayed on the Game Over screen.
10. Press any key to start a new game.

## 🏆 Scoring System

The game calculates the score based on the level reached.

The scoring formula used is:

\[
\text{Score} = 10 \times 2^{(\text{Level}-1)}
\]

| Level | Score |
|---|---:|
| 1 | 10 |
| 2 | 20 |
| 3 | 40 |
| 4 | 80 |
| 5 | 160 |

The score increases exponentially as the player progresses through the levels.

## 📂 Project Structure

```text
Simon-Says-Memory-Game/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/ShyamKumarChaurasiya/Simon-Says-Memory-Game.git
```

### 2. Navigate to the Project Folder

```bash
cd Simon-Says-Memory-Game
```

### 3. Run the Game

Open `index.html` in your preferred web browser.

Alternatively, use the **Live Server** extension in Visual Studio Code.

No additional installation is required.

## 📚 What I Learned

Through this project, I practiced:

- Using JavaScript arrays to store game sequences
- Generating random values using `Math.random()`
- Selecting and manipulating DOM elements
- Handling keyboard and mouse events
- Implementing conditional logic for game progression
- Managing game state using variables
- Using `setTimeout()` for animations and delayed actions
- Creating interactive browser-based games
- Implementing a scoring system using mathematical formulas

## 🔮 Future Improvements

Possible enhancements for this project include:

- Adding sound effects for button presses
- Implementing a high-score system
- Adding difficulty levels
- Improving mobile and touch-screen support
- Adding a start and restart button
- Creating a leaderboard
- Adding a countdown timer

## 👨‍💻 Author

**Shyam Kumar Chaurasiya**

- GitHub: https://github.com/ShyamKumarChaurasiya

---

⭐ If you find this project interesting, consider giving the repository a star!
