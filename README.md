# Mahjong-Style Game with Pygame

## Introduction
Create a Mahjong-style game using Python and Pygame. In this game, the objective is to match pairs of tiles on a board until all pairs have been matched. When all pairs are matched, the player wins, and the game can be reset.

## Features
- A game board with a grid of face-down tiles.
- Tiles with different symbols or images.
- Ability to select two tiles at a time to see if they match.
- If the selected tiles match, they are removed from the board.
- A timer to track the player's progress.
- A win condition that triggers when all tiles have been matched.
- Option to reset the game and start over.

## Game Flow
1. Display the game board with face-down tiles.
2. Allow the player to select two tiles.
3. Check if the selected tiles match:
   - If they match, remove them from the board.
   - If they don't match, flip them back face-down.
4. Repeat steps 2-3 until all pairs have been matched.
5. When all pairs are matched, display a win message.
6. Offer an option to reset the game.

## Pseudo Code
```python
#import necessary packages
# Initialize Pygame
# Define constants (e.g., screen size, tile size, images)
# Create a function to set up the game board
# Create a function to handle tile selection and matching
# Create a function to check for a win condition
# Main game loop
# Event handling (e.g., mouse clicks)
# Draw the game board and tiles
# Display the timer
# Check for a win condition
# Reset the game when the player wins or chooses to restart
