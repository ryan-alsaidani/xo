XO Game — JavaScript

This repository contains my implementation of a simple Tic Tac Toe (XO) game using HTML, CSS, and JavaScript.
The game is lightweight, clean, and made for practice and personal learning.

Repository: https://github.com/ryan-alsaidani/x_o_game_js


---

📌 Description

2-player style logic,(no bot).

The game does not detect draws — it only tracks how many times X won and how many times O won.

The score is stored using localStorage so it stays saved even after refreshing the page.

The board is fully clickable and updates dynamically using images for X and O.



---

🧠 Features

✔️ Dynamic XO board

✔️ Clickable cells that prevent overwriting (cannot click a non-empty square)

✔️ New Game button → clears the board only

✔️ Remove Score button → resets win counters back to 0

✔️ Score is saved between sessions via localStorage

✔️ Clear and simple code structure



---

📥 Installation

git clone https://github.com/ryan-alsaidani/x_o_game_js.git

Then open:

index.html

in your browser.


---

🎮 Usage

Click any empty cell to place your mark (X or O).

Turns alternate automatically.

When a winner is detected, the win counter increases.

New Game → clears the grid.

Remove Score → resets both players’ scores to zero.



---

📝 License

This project is licensed under the MIT License, allowing free use, modification, and distribution.
