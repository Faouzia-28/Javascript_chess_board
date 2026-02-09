♟️ JavaScript Chess Game

A fully interactive browser-based Chess game built using HTML, CSS, JavaScript, and jQuery.
The game implements core chess mechanics including legal move validation, turn-based play, piece capturing, and castling, all without using any external chess libraries.

✨ Features

Complete 8×8 chessboard with algebraic notation (a–h, 1–8)

Turn-based gameplay (White vs Black)

Legal move highlighting for each piece

Piece capturing logic

Special moves support:

Castling (King + Rook)

Visual animations and hover effects

Smooth UI with neon highlights and interactive transitions

Right-click disabled to avoid accidental interactions

🛠️ Technologies Used

HTML5 – Game structure and board layout

CSS3 – Styling, animations, hover effects

JavaScript (ES6) – Game logic and state management

jQuery – DOM manipulation and event handling

📂 Project Structure
├── index.html      # Chessboard layout and UI
├── style.css       # Styling, animations, and effects
└── script.js       # Game logic, rules, and interactions

🚀 How to Run

Clone the repository

git clone https://github.com/your-username/javascript-chess-game.git


Open index.html in any modern web browser

Start playing 🎯

No server or additional setup required.

🧠 Game Logic Overview

Each piece is stored as an object with:

Position

Movement state

Capture status

Valid moves are calculated dynamically based on:

Piece type

Board boundaries

Obstructions and opponent pieces

Highlighted cells guide the player’s legal moves

Turn switching is handled after every valid move or capture

📌 Future Improvements (Optional)

Check / Checkmate detection

Pawn promotion

En passant move support

Undo / redo moves

AI opponent

👩‍💻 Author

Faouzia V
Built as a JavaScript logic and UI interaction project.
