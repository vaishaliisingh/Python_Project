# Rock-Paper-Scissors Game

## Project Overview
This is a Python-based implementation of the classic Rock-Paper-Scissors game. The game includes two modes: Player vs. Computer and Player vs. Player. In Player vs. Player mode, the choices (Rock, Paper, Scissors) are assigned randomly to the numbers (1, 2, 3) to ensure fairness and maintain an element of surprise. The game features user input validation, randomized computer choices, and dynamic result determination for an interactive and enjoyable gaming experience.

## Features
- Two game modes: Player vs. Computer and Player vs. Player.
- In Player vs. Player mode, choices are randomly assigned to numbers to keep them hidden until both players have made their selections.
- User input validation to ensure correct choices.
- Randomized computer choices for unpredictability.
- Clear instructions and result announcements.
- Replay option to continue playing without restarting the program.

## How to Play
1. **Player vs. Computer Mode**: 
   - The player selects their choice (Rock, Paper, or Scissors).
   - The computer randomly selects its choice.
   - The winner is determined based on the classic rules: Rock crushes Scissors, Scissors cuts Paper, and Paper covers Rock.

2. **Player vs. Player Mode**:
   - Both players independently select their choices (1, 2, or 3) without knowing which number corresponds to Rock, Paper, or Scissors.
   - After both players have made their selections, the choices are revealed and the winner is determined.

## Usage
1. Run the `rock_paper_scissors.py` script.
2. Follow the on-screen prompts to select the game mode.
3. Enter your choices as instructed.
4. View the results and decide whether to play again.

## Code Highlights
- **Input Validation**: Ensures players select valid choices.
- **Randomized Choices**: Uses Python's `random` module to shuffle choices in Player vs. Player mode and generate computer choices in Player vs. Computer mode.
- **Dynamic Results**: Determines and displays the winner based on game rules.

## Example
```python
Enter your choice 
 1 - Rock 
 2 - Paper 
 3 - Scissors 

Player 1, enter your choice (1, 2, or 3): 1
Player 2, enter your choice (1, 2, or 3): 3
Player 1 choice: Rock
Player 2 choice: Scissors
Rock vs Scissors
Player 1 wins!

Do you want to play again? (Y/N): n
Thanks for playing!
