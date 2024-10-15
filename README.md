# Tower of Hanoi Game

## Overview

The Tower of Hanoi is a classic mathematical puzzle that consists of three rods and a number of disks of different sizes which can slide onto any rod. The puzzle starts with the disks stacked in ascending order of size on one rod, the smallest at the top. The objective of the puzzle is to move the entire stack to another rod, obeying the following rules:

1. Only one disk can be moved at a time.
2. Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty rod.
3. No disk may be placed on top of a smaller disk.

This HTML project allows users to play the Tower of Hanoi game interactively through a simple web interface.

## Files Structure

- `index.html`: Contains the HTML structure of the game.
- `styles.css`: Contains the styles and layout for the game interface.
- `hanoi.js`: Contains the logic to perform moves based on user input.
- `tower.js`: Possibly includes additional game functionalities and event handling.

## Usage

1. Clone or download the repository.
2. Open the `index.html` file in a web browser.
3. Enter the number of disks in the input field.
4. Click the "Make Move" button to move the disks according to the Tower of Hanoi rules.

## Setting Up the Game

To set up the game, follow these steps:

1. **Enter Number of Disks**: Use the input field to specify how many disks you want the game to utilize (e.g., 3, 4, 5).
2. **Make a Move**: After entering the number of disks, click on the "Make Move" button to execute the next valid move in solving the puzzle.

## Code Description

### `index.html`

This file acts as the entry point of the Tower of Hanoi game. It includes input fields for the player, links to external CSS for styling, and JavaScript files that handle the game logic.

### `styles.css`

This file styles the game ensuring a pleasant user experience. The styles are defined to format the layout of disks, rods, and buttons appropriately.

### `hanoi.js`

The core logic of the game is managed here, determining how moves should be made according to the Tower of Hanoi rules. Functions handle the movement of disks between rods and validate the player's input.

### `tower.js`

This file may include additional functionalities, such as event listeners for buttons and updating the game display dynamically after each move.

## Contributing

If you would like to contribute to the project, feel free to create a pull request or open an issue for discussion. Contributions can include bug fixes, additional features, or enhancements in the code.

## License

This project is open-source and available under the MIT License.

## Acknowledgements

Special thanks to resources that provided information on the Tower of Hanoi puzzle, including algorithm references and coding techniques.

Feel free to modify this README to fit your project's details and future improvements.
