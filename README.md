# Pig Game

Welcome to the Pig Game! This is a simple two-player dice game implemented using HTML, CSS, and JavaScript.

## Game Rules

1. The game is played by two players.
2. Players take turns rolling a single die as many times as they wish. Each result gets added to their round score.
3. If the player rolls a 1, their round score is lost, and it becomes the next player's turn.
4. Players can choose to 'Hold', which means that their round score gets added to their total score, and it becomes the next player's turn.
5. The first player to reach or exceed 100 points on their total score wins the game.

## Project Structure

### HTML

The HTML file sets up the basic structure of the game. It includes sections for each player, the dice image, and buttons for rolling the dice, holding the score, and starting a new game.

### CSS

The CSS file styles the game interface. It includes styles for the main game layout, player sections, buttons, and other game elements. The design includes a nice gradient background, player panels, and transitions to enhance the user experience.

### JavaScript

The JavaScript file contains the game logic. It includes functions for initializing the game, rolling the dice, holding the score, and switching players. The key functionalities are:

- **init**: Initializes the game state, including resetting scores and setting the active player.
- **switchPlayer**: Switches the active player when a player rolls a 1 or chooses to hold their score.
- **Event Listeners**: Handles clicks on the roll dice, hold, and new game buttons to update the game state and interface.
