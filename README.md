## Flask Application Design for a Terminal-Based Tetris Game

### HTML Files

- **`index.html`**: The main HTML file containing the game interface. It will include elements such as the game board, score counter, and controls.

### Routes

- **`GET /`**: The root route that serves the `index.html` file, initializing the game.
- **`POST /move`**: The route to handle user input for moving the falling tetromino.
- **`POST /rotate`**: The route to handle user input for rotating the falling tetromino.
- **`POST /drop`**: The route to handle user input for dropping the falling tetromino immediately.
- **`POST /update`**: The route to handle periodic updates of the game state, including the movement of the falling tetromino, collision detection, and line clearance.
- **`POST /endgame`**: The route to handle the end of the game, triggered when the player loses.