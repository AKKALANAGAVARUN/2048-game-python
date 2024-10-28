# 2048-game-python

The following Python script uses the tkinter library to create a graphical user interface for the game 2048. The script defines a class called Game that extends the tk.Frame class and includes methods to create the GUI, start the game, and manipulate the game matrix.

To create the GUI, the script uses Frame and Label widgets to create a 4x4 grid of cells and a score header that displays the player's score. The start_game method initializes the game by creating a 4x4 matrix filled with zeros and randomly placing two 2s on the board. The score is also initialized to 0.

The script includes helper methods to manipulate the game matrix, including stack, which moves all non-zero elements of a row or column to the beginning of the row or column and sets the remaining elements to zero, and merge, which merges adjacent elements of a row or column if they are equal.

The main methods that move the elements of the game matrix are move_left, move_right, move_up, and move_down. These methods update the GUI to reflect the new state of the game board.

To determine if the game is over, the script includes an is_game_over method that checks if there are any empty cells on the board and if any adjacent elements are equal. If the game is over, the game_over method is called to display a message to the player.

Finally, the script includes an update_score method to update the player's score and the score header in the GUI. The script creates an instance of the Game class and starts the game.

Here are three points you can include in your resume for the 2048 game project:

1. **Developed an Interactive 2048 Game**: Engineered an engaging 2048 game utilizing Python and the Tkinter GUI toolkit, enhancing user experience through intuitive design and responsive controls. This project involved implementing core gameplay mechanics, including tile merging and scoring algorithms, to create a seamless gaming experience.

2. **Implemented Advanced Game Logic**: Designed and optimized the underlying logic for tile manipulation, including stacking, combining, and adding new tiles. Employed algorithmic approaches to determine game states (win/lose) and ensure efficient memory management, significantly enhancing performance and responsiveness.

3. **Enhanced User Engagement through Visual Aesthetics**: Leveraged a color-coded grid system to provide visual feedback for tile values, employing industry-standard design principles to improve usability. Integrated dynamic score tracking and game-over notifications to create an immersive and rewarding user interface.

Steps:
Setting Up the Game Class:

    Created a Game class that inherits from tk.Frame, setting up the GUI framework.

Color and Font Definitions:

    Defined color schemes and fonts for the game interface and cells, enhancing the visual appeal.

Grid Initialization:

    Created a 4x4 grid using frames for each cell and labels to display the numbers, implementing a structured layout.

Scoreboard Creation:

    Added a scoreboard at the top to display the current score, making it easy for players to keep track.

Game Start Logic:

    Initialized a matrix to represent the game state and placed two '2' tiles randomly at the start.

Matrix Manipulation Functions:

    Implemented methods to manipulate the game matrix (stacking, combining, reversing, and transposing), essential for handling player moves.

Adding New Tiles:

    Created a method to randomly add new tiles (either 2 or 4) to the grid after each move.

Updating the GUI:

    Designed a method to update the visual representation of the game grid based on the matrix state.

Event Handling for Moves:

    Bound arrow key presses to functions that handle player input and invoke matrix manipulation.

Move Validity Checks:

    Implemented checks to determine if any moves are still possible, both horizontally and vertically.

Game Over Conditions:

    Added logic to check for win (2048 tile) or lose conditions and display appropriate messages to the user.

Main Function:

    Set up the main function to instantiate the Game class, effectively starting the game.
