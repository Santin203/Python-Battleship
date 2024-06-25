# Python Battleship Game

## Introduction
This is a Python-based Battleship game where you can play against the computer AI. The game offers two difficulty levels: Easy and Hard. You can place your ships and attempt to sink the enemy's ships by strategically guessing their positions on the board.

## Requirements
To run the game, ensure you have the following installed:
- Python 3.x
- Libraries: numpy, pandas, IPython

## How to Play
1. **Starting the Game**
   - Run the script in a Python environment.
   - You will be prompted to choose whether you want to play or not (Yes/No).

2. **Game Setup**
   - Select the difficulty level: Easy (5x5 board) or Hard (7x7 board).
   - Place your ships on the board.

3. **Gameplay**
   - You will take turns with the AI to shoot at each other's ships.
   - Enter the row and column to shoot at.
   - If you hit the opponent's ship, the spot will be marked with '*' (Hit), otherwise with 'X' (Miss).
   - The game ends when either you or the AI sink all the opponent's ships.

4. **Display**
   - The boards (Your board and Enemy board) will be displayed side by side after each move, showing the current state of the game.

5. **Winning or Losing**
   - If you sink all of the opponent's ships before they sink yours, you win.
   - If the opponent sinks all of your ships first, you lose.

## Functionality
- **Display Function**: The `display_side_by_side` function allows you to display two Pandas DataFrames (representing boards) side by side in the console for easy viewing.
- **Ship Placement**: Ships are randomly placed on the board at the start of the game.
- **AI Logic**: The AI shoots randomly at your ships without repetition, trying to sink them strategically once it hits a ship.

## Credits
- The `display_side_by_side` function was adapted from Stack Overflow: https://stackoverflow.com/questions/38783027/jupyter-notebook-display-two-pandas-tables-side-by-side

## Future Enhancements
- Implement more advanced AI strategies for better gameplay.
- Add GUI (Graphical User Interface) using libraries like Tkinter or Pygame for a more interactive experience.
- Incorporate multiplayer functionality for online or local play.

## Conclusion
This Battleship game project demonstrates the use of basic Python programming along with libraries like numpy and pandas for board management and display. It offers an engaging gameplay experience suitable for users of all ages.

Enjoy playing Battleship and have fun sinking your opponent's ships!

