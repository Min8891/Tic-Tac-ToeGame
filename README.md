# Tic-Tac-ToeGame
EO – C8 – 19 - 610 -10E                       Program 3  - Project 
Tic-Tac-Toe Game
Write a modular program that allows two players to play a game of tic-tac-toe. Use a two-dimensional char array with three rows and three columns as the game board. Each element of the array should be initialized with an asterisk (*). The program should display the initial board configuration and then start a loop that does the following:
•	Have player 1 select a board location for an X by entering a row and column number. Then redisplay the board with an X replacing the * in the chosen location.
•	If there is no winner yet and the board is not yet full, have player 2 select a board location for an O by entering a row and column number. Then redisplay the board with an O replacing the * in the chosen location.
The loop should continue until a player has won or a tie has occurred, then display a message indicating who won, or reporting that a tie occurred.
•	Player 1 wins when there are three Xs in a row, a column, or a diagonal on the game board.
•	Player 2 wins when there are three Os in a row, a column, or a diagonal on the game board.
•	A tie occurs when all of the locations on the board are full, but there is no winner.
Input Validation: Only allow legal moves to be entered. The row and column must be 1, 2, or 3. The selected board location must currently be empty (i.e., still have an asterisk in it).   
