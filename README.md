# 2048-game-python

The following Python script uses the tkinter library to create a graphical user interface for the game 2048. The script defines a class called Game that extends the tk.Frame class and includes methods to create the GUI, start the game, and manipulate the game matrix.

To create the GUI, the script uses Frame and Label widgets to create a 4x4 grid of cells and a score header that displays the player's score. The start_game method initializes the game by creating a 4x4 matrix filled with zeros and randomly placing two 2s on the board. The score is also initialized to 0.

The script includes helper methods to manipulate the game matrix, including stack, which moves all non-zero elements of a row or column to the beginning of the row or column and sets the remaining elements to zero, and merge, which merges adjacent elements of a row or column if they are equal.

The main methods that move the elements of the game matrix are move_left, move_right, move_up, and move_down. These methods update the GUI to reflect the new state of the game board.

To determine if the game is over, the script includes an is_game_over method that checks if there are any empty cells on the board and if any adjacent elements are equal. If the game is over, the game_over method is called to display a message to the player.

Finally, the script includes an update_score method to update the player's score and the score header in the GUI. The script creates an instance of the Game class and starts the game.
