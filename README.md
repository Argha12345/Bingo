# 🎯 Bingo Game (HTML, CSS, JavaScript)

A fully interactive **5×5 Bingo game** built using **vanilla HTML, CSS, and JavaScript**.  
The game follows realistic Bingo rules with manual board setup, validation, marking, undo support, and automatic Bingo detection.

---

 🚀 Features

🧩 Board Setup
- 5×5 Bingo board (25 cells)
- Users manually enter numbers
- **Input rules enforced:**
  - Numbers must be between **1 and 25**
  - **Duplicate numbers are not allowed**
- Confirmation prompt before starting the game

 🎮 Gameplay
- After confirmation:
  - Numbers become **read-only**
  - Cells are **clickable to mark**
  - Once marked, a cell cannot be unmarked manually
- **Undo button** to revert the last marked cell (error recovery)

🏆 Bingo Logic
- Automatically detects completed:
  - Rows
  - Columns
  - Diagonals
- Each completed line is counted **only once**
- **BINGO is declared when 5 total sets are completed**
  - Example: 1 row + 1 column + 3 diagonals = Bingo

---

🔁 Undo Functionality
- Undo removes the **most recently marked cell**
- Line counts are **recalculated safely**
- Prevents logical inconsistencies
- Disabled automatically when no actions remain

---

 🛠️ Tech Stack

- **HTML** – Structure
- **CSS** – Styling and layout
- **JavaScript** – Game logic and state management

No external libraries or frameworks used.

---

