# Tictactoe-game
Simple Tictactoe game code using Python 

This code is a simple implementation of the Tic-Tac-Toe game in Python. Here's a breakdown of its functionality:

Function sum(a, b, c): This function is defined but not implemented. It's presumably meant to sum three values.

Function printBoard(xState, zState): This function prints the Tic-Tac-Toe board's current state. The board positions are represented by either 'X', 'O', or their respective indices if unoccupied. However, there are repeated variable assignments (three), which will result in incorrect board display.

Function checkwin(xState, zState): This function checks if there's a winning combination in the current board states for 'X' or 'O'. It iterates through possible winning combinations and checks if all positions in a combination are marked by the same player. If 'X' wins, it prints "X won the match"; if 'O' wins, it prints "O won the match".

Main Game Loop: In the main section of the code, the game initializes the board states and alternates turns between 'X' and 'O'. Players input their move, which updates the board state and switches turns until a win is detected.
