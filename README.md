# Rock-Paper-Scissors-js-project
Description
This repository contains the source code for a simple Rock Paper Scissors game implemented using HTML, CSS, and JavaScript. The game allows the user to play against the computer, track their score, and utilize additional features like autoplay and score reset.

Features:

Interactive Gameplay: Click buttons to choose Rock, Paper, or Scissors.
Keyboard Shortcuts: Use 'r' for Rock, 'p' for Paper, 's' for Scissors, 'a' for Autoplay, and 'Backspace' for score reset confirmation.
Autoplay Mode: The computer plays against itself automatically.
Score Tracking: Keeps track of wins, losses, and draws.
Score Reset: Option to reset the score with confirmation.


Installation:

Clone the repository:
bash
Copy code
git clone https://github.com/suspicious-candy/Rock-Paper-Scissors-js-project/.git
Navigate to the project directory:
bash
Copy code
cd rock-paper-scissors


Usage:

Open the index.html file in a web browser:
bash
Copy code
open index.html
Play the game by clicking the Rock, Paper, or Scissors buttons or using the keyboard shortcuts.
View your game results and scores.
Use the "Reset score" button to reset the score and the "AutoPlay" button to enable autoplay mode.
File Structure
index.html: The main HTML file containing the structure of the game.
RPS.css: The CSS file for styling the game.
pics/: Directory containing the images used for the Rock, Paper, and Scissors buttons.


Game Logic:

The game randomly selects a move for the computer and compares it with the player's move to determine the result (win, lose, or draw).
The score is updated based on the result of each game.
CSS Styling
The game has a black background with antique white text for better contrast.
Buttons are styled with a transparent background, white borders, and a cursor pointer for interactivity.
JavaScript Functions
playGame(playerMove): Determines the result of the game based on the player's and computer's moves and updates the score.
pickComputerMove(): Randomly selects a move for the computer.
autoplay(): Automatically plays the game with random moves at a set interval.
resetcon(): Confirms and resets the score.


Contributing:

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

Inspiration :
https://www.youtube.com/watch?v=EerdGm-ehJQ&t=36616s

Acknowledgments
Thank you for trying out the Rock Paper Scissors game! Have fun playing!
