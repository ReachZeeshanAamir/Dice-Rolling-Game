# Dice Rolling Game Documentation

## Overview
This Python code implements a simple dice rolling game where players take turns rolling a six-sided die. Each player aims to accumulate points until one player reaches or exceeds a maximum score (default set to 50). The game supports 2 to 4 players and provides interactive prompts for rolling the dice. The player with the highest score when the game ends is declared the winner.

## Key Components
- **Dice Rolling Function:** Generates a random number between 1 and 6 to simulate rolling a six-sided die.
- **Input Validation:** Ensures that the number of players entered is between 2 and 4.
- **Player Turn Mechanism:** Allows each player to take turns rolling the dice until they choose to stop or roll a 0.
- **Scoring System:** Tracks the scores of each player and calculates the total score after each turn.
- **Game End Condition:** Continues the game until one player reaches or exceeds the maximum score.

## How It Works
1. The game prompts the user to enter the number of players (2 - 4).
2. Each player takes turns rolling the dice by choosing to roll or stop.
3. If a player rolls a 0, their turn ends, and their current score is reset to 0.
4. The game continues until one player's total score reaches or exceeds the maximum score.
5. The player with the highest score at the end of the game is declared the winner.

## Code Structure
The code consists of two main parts:
- **Initialization:** Sets up the game by prompting the user for the number of players and initializing player scores.
- **Game Loop:** Continuously loops through each player's turn until the game ends, updating scores and checking for the winning condition.

## Limitations
- The maximum score and number of players are fixed and not customizable within the game.
- Limited user interaction and feedback during gameplay, with minimal error handling for invalid inputs.
- Lack of customization options for game parameters such as the maximum score or dice size.

## Future Enhancements
- Add support for customizable game parameters such as maximum score and number of players.
- Enhance user interaction with clearer instructions and feedback during gameplay.
- Implement error handling for invalid inputs and edge cases to improve robustness.
- Introduce additional features such as player names, customizable dice, or special rules to add depth to the game.

With this documentation, you should have a clear understanding of how the dice rolling game works and its key components.
