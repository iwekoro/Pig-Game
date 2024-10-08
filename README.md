# Pig Game

## Overview

Pig Game is a simple two-player dice game where players take turns to roll a dice. The objective is to be the first player to reach a score of 100. The game is built using HTML, CSS, and JavaScript, and it includes responsive design to work well on both desktop and mobile devices.

## Features

- **Two Players**: Play as Player 1 or Player 2.
- **Roll Dice**: Roll the dice to accumulate points in your current score.
- **Hold**: Save your current score to your total score and pass the turn to the other player.
- **Winning Condition**: The first player to reach 100 points wins the game.
- **New Game**: Start a new game at any time.

## Technologies Used

- **HTML5**: For the structure of the game.
- **CSS3**: For styling and responsive design.
- **JavaScript (ES6)**: For the game logic and interactivity.

## How to Play

1. Open the game in your web browser.
2. The game starts with Player 1.
3. On your turn, click **Roll Dice** to roll the dice:
   - If you roll a 2-6, the number is added to your current score.
   - If you roll a 1, your turn ends, and you lose your current score for that turn.
4. Click **Hold** to add your current score to your total score and pass the turn to the other player.
5. The first player to reach 100 points wins the game.
6. Click **New Game** to reset the game at any time.

## Responsive Design

The game is designed to be responsive and works on both desktop and mobile devices:

- On larger screens, the players' sections are displayed side by side.
- On smaller screens, the players' sections are stacked vertically for better readability and accessibility.
- Buttons and the dice image adjust in size and positioning based on the screen size.

## Installation and Setup

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/iwekoro/Pig-Game.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pig-game
   ```
3. Open the `index.html` file in your web browser to start the game.

## Project Structure

```plaintext
├── index.html        # The main HTML file
├── style.css         # The CSS file for styling
├── script.js         # The JavaScript file containing game logic
└── README.md         # Project documentation (this file)

```
