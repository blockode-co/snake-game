# Simple Snake Game

This is a simple implementation of the classic Snake game using HTML5 Canvas and JavaScript.

## How to Play

1.  Save the `index.html` file to your computer.
2.  Open the file in any modern web browser (Chrome, Firefox, Safari, Edge, etc.).
3.  Use the arrow keys (Up, Down, Left, Right) to control the snake's direction.
4.  The goal is to eat the red apples to increase your score and grow the snake.
5.  Avoid colliding with the walls (the edges of the canvas) or with the snake's own body.
6.  If the snake collides with itself, the game is over.  You'll be prompted to restart.

## Features

*   Classic Snake gameplay.
*   Score tracking.
*   Collision detection (snake vs. self).
*   Wrap-around: The snake can go off one edge of the screen and reappear on the opposite edge.
*   Game Over screen displayed on the canvas.
*   Restart game option.
*   Arrow key controls.

## Controls

*   **Up Arrow:** Move the snake up.
*   **Down Arrow:** Move the snake down.
*   **Left Arrow:** Move the snake left.
*   **Right Arrow:** Move the snake right.

## Implementation Details

*   **HTML5 Canvas:** The game is rendered using the HTML5 Canvas element.
*   **JavaScript:** The game logic and rendering are implemented in JavaScript.
*   **Grid-based movement:** The game board is divided into a grid, and the snake moves in increments of the grid size.
*   **Game Loop:**  The `setInterval` function is used to create a game loop, which updates the game state and redraws the canvas at regular intervals.
*   **Object-Oriented Principles:** While not strictly object-oriented, the game is structured with functions for updating the game state, drawing the game elements, and handling user input.

## Customization

*   **`gridSize`:**  Change the size of the grid cells in the `gridSize` variable.  Smaller values will make the snake move faster and the game more difficult.
*   **`gameSpeed`:**  Adjust the game speed (in milliseconds) by changing the `gameSpeed` variable. Lower values make the game faster.
*   **Colors:** Modify the `fillStyle` properties in the `draw()` function to change the colors of the snake, apple, and background.
*   **Canvas Size:** Adjust the `width` and `height` attributes of the `<canvas>` element in the HTML to change the size of the game board.  Make sure to update `tileCount` accordingly.

## Known Issues

*   The game can be a little too easy.  Increasing the speed or making the grid size smaller will make it more challenging.
*   The collision detection is based on grid coordinates, so it's possible for the snake to appear to overlap slightly before a collision is registered.

## Future Enhancements

*   Add more levels with increasing difficulty.
*   Implement different types of apples with special effects (e.g., speed boost, score multiplier).
*   Add sound effects.
*   Implement a high score system (using local storage).
*   Improve the visual design.
*   Add touch controls for mobile devices.

## License

This project is open-source and available under the [MIT License](LICENSE).  (You can create a LICENSE file if you want to specify a license, but it's optional for personal projects).
