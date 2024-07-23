# Tic Tac Toe Game Project

## Overview

This project is a Tic Tac Toe game built with React.js, utilizing hooks like useState and useEffect to manage state and side effects. The game allows players to edit and save their names, provides a clear and engaging user interface, and displays the game result (win or draw) through a modal.

## Features

Player Name Editing:

Players can edit and save their names using an input field at the top panel.
The names are displayed dynamically throughout the game.
Game Logic:

Utilizes React hooks like useState to manage the game state, including the current player, game board, and game status.
The game board is a 3x3 grid where players take turns to place their marks (X or O).
The game checks for a win condition after each move and displays the winner’s name in a modal.
If all cells are filled without a winner, a draw message is displayed.
Winner Modal:

A modal pops up to announce the winner when a player wins the game.
If the game ends in a draw, a corresponding message is displayed in the modal.
React Hooks:

useState is used to handle the state of the game board, current player, and player names.
useEffect can be used to handle side effects such as resetting the game state or triggering animations when the game status changes.

## Future Enhancements

Implementing a scoreboard to track wins and draws over multiple games.
Adding animations and sound effects for a more engaging user experience.
Implementing an AI opponent for single-player mode.

[tictactoeGameVideo](https://youtu.be/-nDQ5YEI7ok)
