# Dice Game 🎲

A simple, interactive two-player dice game built with JavaScript, HTML, and CSS. Players take turns rolling a dice, accumulating points until they choose to hold or roll a 1, which ends their turn. The first player to reach or exceed the target score (20 by default) wins the game.

## How to Play

1. **Roll the Dice**: Players take turns clicking the **Roll Dice** button. A random number between 1 and 6 is generated and displayed as a dice image.

   - If the dice shows **1**, the player loses their current turn points and the turn switches to the other player.
   - If the dice shows any other number, it’s added to the player’s current turn points.

2. **Hold Points**: Click the **Hold** button to add the current turn points to your total score. This action ends the player’s turn, switching control to the other player.

3. **Winning the Game**: The first player to reach or exceed **20 points** wins. A message will announce the winner, and the winning player’s section will highlight in color.

4. **New Game**: Click the **New Game** button to reset scores and start a new game, with the previous winner going second.

## Project Structure

- **HTML**: Defines the structure and layout of the game.
- **CSS**: Styles the game, setting up visuals for player sections, buttons, and other UI elements.
- **JavaScript**: Contains the game logic:
  - Initializes game state and players
  - Handles dice rolls, turn switching, score holding, and win conditions

## Code Explanation

The main code sections include:

- **Initialization**: Sets the game’s initial state, clearing scores and choosing the starting player.
- **Event Listeners**: Three main buttons control the game:
  - **Roll Dice**: Generates a random number between 1-6 and updates the current turn score.
  - **Hold**: Adds the current score to the player's total and checks for a win.
  - **New Game**: Resets the game for a fresh start.
- **Switching Turns**: If a player rolls a 1, their turn ends, and control passes to the other player.
- Also tracks the winning statistic of each player.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/Ozyugoo/Dice-Game.git

   ```

2. Open the index.html file in a web browser to play the game locally.

## Requirements

No external dependencies are required. This game runs entirely in the browser with basic JavaScript, HTML, and CSS.

## Future Enhancements

- Add custom winning score input.
- Enhance UI with animations.
