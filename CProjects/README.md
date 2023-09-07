Tic Tac Toe Game 🎮
===================

This is a simple command-line implementation of the classic game Tic Tac Toe (also known as Noughts and Crosses) in C. You can play the game against another player. Follow the instructions below to play the game.

Table of Contents
-----------------

-   Introduction
-   How to Play
-   Game Rules
-   Getting Started
-   Gameplay
-   Menu
-   Terminating the Game
-   Acknowledgements

Introduction 📜
---------------

This C program allows two players to take turns marking the spaces in a 3x3 grid with their respective symbols (X and O). The first player to get three of their symbols in a row, column, or diagonal wins the game.

How to Play 🕹️
---------------

1.  Player 1 is assigned the symbol 'X', and Player 2 is assigned the symbol 'O'.
2.  Players take turns entering the number of the cell they want to mark.
3.  The game board is displayed after each move to help players visualize the current state of the game.
4.  The game continues until one player wins or there is a draw (all cells are filled).

Game Rules 📋
-------------

-   Players take turns making moves.
-   The player who successfully places three of their symbols in a row, column, or diagonal wins the game.
-   If all cells are filled, and no player has won, the game ends in a draw.

Getting Started 🚀
------------------

To start the game:

1.  Compile the code using a C compiler.
2.  Run the executable.

Gameplay 🎯
-----------

The game begins with an empty 3x3 grid displayed on the screen with cell numbers as references. Players enter the cell number they want to mark with their symbol. The game board is updated after each move.

Example game board:

luaCopy code

 `1  |  2  |  3
  ----------------
    4  |  5  |  6
  ----------------
    7  |  8  |  9`

Menu 📋
-------

After each game, you will be presented with a menu that allows you to choose between restarting the game or exiting.

Options:

-   Press `1` to restart the game.
-   Press `0` to exit the program.

Terminating the Game ❌
----------------------

To exit the game at any time, enter `-1` when prompted for a cell number.

Acknowledgements 🙌
-------------------

This Tic Tac Toe game was created in C by Prateek Srivastava. Have fun playing! 🎉

Enjoy the game and thanks for playing Tic Tac Toe! 😃
