# Connect4_CSC321
## Info
**Author:**
Filip Segota  
**Class:**
CSC 321 (Programming 3), Spring 2021  
**Assignment:**
Connect 4 Lab

## Overview
Create a program to simulate the playing of Connect 4. Create all the classes needed to play the game and then create a GUI for it. Besides the program, create documentation consisting of reports, testing, a use case, UML, and activity diagrams.

## Rules of Connect 4
Two players (different colors) take turns dropping colored tokens into a six-row, seven-column board. The token occupies the lowest available spot within the column. The goal is to be the first one to form a horizontal, vertical, diagonal line of four one's own tokens.

## Requirements
  - Two players able to play the game
  - Players have name, id, and color
  - Board that can change and access its fields, check if the move is legal, and check if the game is over
  - Driver that will run the game using the instance of the Game class
  - Game object can run the game, start it, make a move, finish the game, and everything else required for these functions
  - GUI platform

## Activity Diagram
  - Board is created and each spot is initialized to empty
  - Players 1 and 2 are created with name and color. The current player is set to either player 1 or 2.
  - Start of the game:
    - The current player puts the input:
      - If move is legal, change the board according to input
      - If move is illegal, display a message and go back to current player move
    - If the game is not finished, switch the current player and do the same thing with the other player
    - If the game is finished (Connect 4 or draw), display the result message and end the game
