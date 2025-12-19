# 2048 Game

2048 Game is a classic single-player puzzle game where the main goal is to combine numbered tiles on a 4×4 grid to reach the tile with the value 2048.
The player moves tiles in four directions (up, down, left, right). When two tiles with the same number collide, they merge into one with their combined value. The game requires logical thinking, planning moves ahead, and strategy to achieve the highest possible score.

The project demonstrates core concepts of game logic, state management, and user interaction in a simple and intuitive interface.

Experience the live website: 2048 Game

# Technologies Used

- JavaScript (ES6+) – implementation of game logic, including tile movement, merging rules, score calculation, game state management, and keyboard controls

- HTML5 – structure of the game interface and layout of the game board

- CSS3 – styling of the game field, tiles, states (win/lose), and UI elements

- DOM API – interaction with page elements, rendering the game state, handling user input and updates

- Keyboard Events (keydown) – handling player input via arrow keys

# Setup & Installation

Follow these steps to run the project locally:

1. Clone the repository
git clone https://github.com/viktoriamyhailiak/2048-game.git
cd 2048-game

2. Install dependencies
npm install or yarn install

3. Run the project locally
npm start or yarn start

# Features

Classic 2048 gameplay on a 4×4 grid

Keyboard controls using arrow keys

Tile merging logic with correct rules (no double merge in one move)

Random tile generation (2 or 4 with 10% probability for 4) after each valid move

Score tracking based on merged tile values

Win detection when a tile reaches 2048

Game over detection when no more moves are available

Start / Restart functionality with full game reset

Clean separation of game logic and UI