# Rock-Paper-Scissors Game

## Overview
This is a command-line implementation of the classic **Rock-Paper-Scissors** game, where a user competes against the computer. The game supports **Best of 3** or **Best of 5** modes, with real-time score tracking and a final winner announcement.

## Features
- **Game Mode Selection**: Choose between Best of 3 or Best of 5 rounds.
- **Validated User Input**: Ensures only valid choices (rock, paper, scissors) are accepted.
- **Randomized Computer Choice**: Ensures fair gameplay.
- **Score Tracking**: Displays real-time updates after each round.
- **Final Summary**: Announces the game winner and provides a motivational quote.

## How to Play
1. Run the script in a Python environment.
2. Choose the game mode by entering **3** (Best of 3) or **5** (Best of 5).
3. Enter **rock, paper, or scissors** for each round.
4. The game tracks scores and announces the winner at the end.

## Requirements
- Python 3.x

## Code Structure
- `get_user_choice()`: Handles user input validation.
- `get_computer_choice()`: Generates a random choice for the computer.
- `determine_winner()`: Determines the winner based on game rules.
- `get_game_mode()`: Allows mode selection (Best of 3 or 5).
- `play_game()`: Manages the game flow and displays results.

## Optimizations
- **Modular structure**: Enhances readability and maintainability.
- **Robust input validation**: Prevents invalid entries.
- **User-friendly prompts**: Improves game experience.
- **Concise and structured output**: Provides clear feedback after each round.

## Example Output
```
Welcome to Rock, Paper, Scissors!
Choose game mode: Best of 3 or Best of 5? (Enter 3 or 5): 3
Enter rock, paper, or scissors: rock
Computer chose: scissors
You win this round!
Score -> You: 1 | Computer: 0
...
Game Over!
Congratulations! You won the game!
```

## Author
Developed by Vikas Kumar Singh.

