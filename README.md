# Simon-Game
This is a web-based recreation of the classic Simon Game that tests your memory by generating and playing a sequence of colors and sounds, which the user must repeat in the same order.

<img width="1440" alt="Image" src="https://github.com/user-attachments/assets/08ad1048-deb6-4b4a-ae96-6f6e310b23d1" />

Game Objective:
Repeat the sequence of colors played by the game. Each round adds a new color to the sequence, testing your memory and reflexes. One wrong move — and it's game over!

How to Play:
Press any key to start.
The game will show you a color sequence — one new color gets added each level.
Repeat the sequence by clicking the buttons in the correct order.
Make a mistake? The game ends and you can start over by pressing any key again.

Features:
Interactive UI with four colored buttons: Red, Blue, Green, Yellow
Sound effects for each color using .mp3 files
Animated button press feedback
Auto-incrementing levels
Restart mechanism after game over
Responsive keyboard start control (any key to begin)

Project Structure:
├── index.html       # HTML structure of the Simon Game
├── styles.css       # Styles for layout, buttons, animations
├── game.js          # Core game logic using jQuery
├── sounds/
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   ├── yellow.mp3
│   └── wrong.mp3

Technologies Used
HTML5 – Structure of the game
CSS3 – Styling and animations
JavaScript – Game logic
jQuery – DOM manipulation and event handling
Audio – Sound feedback using .mp3 files

Inspired By
This project is inspired by the classic Simon Game and designed as part of web development practice. Great for building memory-based logic and DOM manipulation skills.
