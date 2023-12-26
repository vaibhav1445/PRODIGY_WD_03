# PRODIGY_WD_03

HTML Structure:
Title and Container: The web app begins with a title and a container div to hold the game board, status messages, and a reset button.
Game Board: Inside the container, there's a div for the game board. This div contains nine cells representing the Tic Tac Toe grid.
Status Display: A div element to display game status messages (e.g., current player's turn, winner, or draw).
Reset Button: A button that allows players to reset the game.


CSS Styling:
Container Styling: Centered alignment, margin for spacing.
Game Board Styling: Displayed as a grid layout to represent the Tic Tac Toe board. Each cell styled to be a square with a border.
Status Display Styling: Positioned below the game board, possibly with bold text for emphasis.
Reset Button Styling: Simple button styling, placed below the status display.


JavaScript Functionality:
Variables: Maintain variables to track the current player, game status (active or ended), and the game board state (array representing each cell's value).
Click Event Listeners: Attach click event listeners to each cell on the game board. When a cell is clicked, execute a function to handle the player's move.
Handle Cell Click Function: Update the game state upon a valid cell click, check for a win or draw condition, change the current player, and update the status display accordingly.
Check Win Function: Evaluate the game board against predefined win conditions to determine if a player has won.
Reset Game Function: Reset all game-related variables, clear the board, and set the initial status message for a new game.
