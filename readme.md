# ✨ Tic Tac Toe Game

A simple and interactive **Tic Tac Toe** game built using **HTML**, **CSS**, and **JavaScript**. Two players can play on the same device. The interface highlights the winner and allows restarting or resetting the game.


---

## 🌐 How to Play

- Two players take turns marking a 3×3 grid with **X** or **O**.
- The first player to place three marks in a horizontal, vertical, or diagonal row wins.
- Click **"New Game"** to start again after a win.
- Click **"Reset Game"** to clear the board at any time.

---

## 🎮 Game Features

- 3x3 interactive grid using `button` elements.
- Real-time turn indication and move handling.
- Winner detection with congratulatory message.
- Visual distinction for X and O players.
- **New Game** and **Reset Game** buttons to replay or restart the game.

---

## 🧠 JavaScript Logic (index.js)

### ✅ Core Concepts

- **Player Turn Handling** using a boolean `turnO` variable (`true` = O, `false` = X).
- **Win Conditions** stored in `winPatterns` (8 possible combinations).
- Event listeners attached to each `.box` to handle player moves.
- DOM manipulation to update game UI and control logic.

### 🧩 Functions Breakdown

- `playTurn()` – Handles the marking and turn switch.
- `checkWinner()` – Checks all 8 winning combinations after every move.
- `showWinner(winner)` – Displays the winner message and disables all boxes.
- `resetGame()` – Resets all variables and clears the grid.
- `disableBoxes()` & `enableBoxes()` – Controls box state after game ends or restarts.

---

## 🧑‍🎨 Styling (index.css)

- **Layout:**
  - Uses Flexbox to center game board and message box.
- **Game Board:**
  - Grid layout (3x3) made with styled `button` elements.
  - Hover and focus removed for a clean interface.
- **Colors:**
  - Background: Soft teal
  - X: Blue, O: Pink
  - Winner message and buttons styled for emphasis.
- **Responsiveness:**
  - Centralized layout adapts well to screen sizes.

---

## 📷 Screenshots

*(Replace with your screenshots)*

| Gameplay | Winner Message |
|---------|----------------|
| ![Gameplay](https://via.placeholder.com/300x300.png) | ![Winner](https://via.placeholder.com/300x300.png) |

---

## 🛠️ Technologies Used

- HTML5
- CSS3 (Flexbox, Custom Buttons)
- JavaScript (Vanilla JS for DOM and logic)

---

## 🧪 To Run Locally

1. Clone the repo or download the code.
2. Open `index.html` in a browser.
3. Start playing!

---

## 📌 Future Improvements (Optional Ideas)

- Add player vs computer mode.
- Add animation or sound effects.
- Add score tracking across rounds.
- Make it mobile responsive with media queries.

---

## 🙋‍♂️ Author

**Prateek Kumar**  
Computer Science student at Chitkara University.

---

## 📄 License

This project is open-source and available for educational or personal use.

---


