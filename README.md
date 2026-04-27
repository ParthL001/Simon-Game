🎮 Simon Game

A fun and interactive memory game built using HTML, CSS, JavaScript, and jQuery. The game challenges players to remember and repeat an increasing sequence of colors.

📌 Project Overview

The Simon Game is a classic memory-based game where the system generates a random sequence of colors, and the player must repeat the sequence correctly. With each level, the sequence becomes longer and more challenging.

🚀 Features
🎯 Random color sequence generation
🔊 Sound effects for each button
💡 Visual animations for user interaction
📈 Level progression system
❌ Game over detection with restart option
🛠️ Technologies Used
HTML5 – Structure of the game
CSS3 – Styling and animations
JavaScript (ES6) – Game logic
jQuery – Event handling and DOM manipulation
📂 Project Structure
Simon-Game/
│── index.html      # Main HTML file
│── styles.css      # Styling
│── game.js         # Game logic
│── sounds/         # Sound effects (red, blue, green, yellow, wrong)
▶️ How to Run

Download or clone the repository:

git clone https://github.com/ParthL001/Simon-Game.git
Open the project folder.
Run the game:
[text](https://parthl001.github.io/Simon-Game/)
🎮 How to Play
Press any key to start the game.
Watch the sequence of colors carefully.
Click the buttons in the same order.
Each level adds a new color to the sequence.
If you make a mistake, the game ends.
Press any key to restart.
🧠 Game Logic 
The game stores:
gamePattern → generated sequence
userClickedPattern → player input
Each level:
A new random color is added
User input is checked step-by-step using a validation function
If incorrect:
Game resets and shows "Game Over"