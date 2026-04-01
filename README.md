# Single-File Games 🎮

A collection of classic browser games — each game is a single, self-contained HTML file with no dependencies or installs required.

## 🕹️ Play

Open the served `index.html` page in your browser to browse and launch all available games.

## 🗂️ Games

| Game | Description |
|------|-------------|
| 🐍 [Snake](games/snake.html) | Eat food, grow longer, avoid the walls |
| ⭕ [Tic-Tac-Toe](games/tictactoe.html) | Play vs a friend or the minimax AI |
| 🃏 [Memory Cards](games/memory.html) | Flip and match pairs of cards |
| 🧱 [Breakout](games/breakout.html) | Bounce the ball and break all the bricks |
| 🔢 [2048](games/2048.html) | Slide tiles and reach 2048 |
| 💣 [Minesweeper](games/minesweeper.html) | Uncover safe squares and flag the mines |

## 🚀 How to Use

1. Clone or download this repository.
2. Serve the repository with a simple static web server (or use GitHub Pages).
3. Open the served `index.html` URL in a modern browser.
4. Click a game card to start playing instantly.

All games run entirely in the browser with no build step or dependencies.  
Note: opening `index.html` directly with `file://` is not supported for automatic game discovery.

## ➕ Adding a New Game

1. Add a new `.html` file to `games/`.
2. Commit and push.

The homepage auto-discovers `games/*.html` and creates a card automatically, so no manual `index.html` card edits are needed.
