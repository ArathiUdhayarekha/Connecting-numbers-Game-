# Connect Numbers Game - Enhanced

## Overview
The Connect Numbers Game is an interactive web-based game where players connect numbers in ascending order on a grid. The game is designed to be engaging and challenging, with varying difficulty levels and a scoring system based on performance.

## Features
- **Dynamic Grid**: The game features a grid that adjusts based on the selected difficulty level (Easy, Medium, Hard).
- **Timer**: Players have a limited time (30 seconds) to connect the numbers.
- **Scoreboard**: Keeps track of top scores based on difficulty, moves, and time taken.
- **Responsive Design**: The game is optimized for both desktop and mobile devices.
- **Instructions**: Clear instructions are provided to guide players on how to play.

## Technologies Used
- HTML5
- CSS3
- JavaScript

## Getting Started
To run the Connect Numbers Game locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd connect-numbers-game
   ```

2. **Open the HTML File**:
   Open `index.html` in your web browser.

3. **Play the Game**:
   - Select a difficulty level from the dropdown menu.
   - Click the "Start / Restart" button to begin the game.
   - Connect numbers in ascending order by clicking and dragging on the grid.

## Game Instructions
1. Choose a difficulty level and start the game.
2. Hold the lowest number (1) and connect numbers in ascending order.
3. Connect numbers only horizontally or vertically (no diagonal moves).
4. You cannot unhold the grid while connecting.
5. Complete the sequence before the 30-second timer runs out.
6. The score increases by 1 point for each successful completion.
7. Your score depends on time taken and number of moves — fewer moves and faster time yield better scores.

## Scoring System
- The score is calculated based on:
  - Difficulty level multiplier
  - Time left when the game is completed
  - Penalty for the number of moves made

## Local Storage
Top scores are saved in the browser's local storage, allowing players to see their best scores even after refreshing the page.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Inspired by classic number connection games.
- Thanks to the open-source community for resources and inspiration.

---

Feel free to modify this README file to better suit your project's needs!
