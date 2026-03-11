Bingo Game using Python Turtle
Project Overview

This project implements a simple luck-based Bingo game using the Python programming language and the Turtle graphics library. The game simulates a traditional bingo environment in which both a player and the computer receive randomly generated bingo cards. Each card consists of a 5 × 5 grid containing numbers from 1 to 35 arranged randomly.

During the game, numbers are drawn randomly. If a drawn number appears on either the player’s grid or the computer’s grid, it is automatically crossed out. The objective of the game is to complete five lines on a grid. A line can be a complete row, column, or diagonal. The first grid that completes five such lines wins the game. If both grids achieve the condition simultaneously, the game ends in a tie.

The graphical interface displays the bingo grids, the numbers drawn during gameplay, and the progress of completed lines for both the player and the computer.

Technologies Used

The project is developed using the following technologies:

Python – Used as the primary programming language for implementing the game logic and functionality.
Turtle Graphics Library – Used to create the graphical interface and display the bingo grids and animations.
Random Module – Used to generate random numbers for bingo cards and number draws.

Project Structure

The project contains the following files:

bingo_game.py – The main Python script that contains the complete implementation of the game.
README.md – Documentation describing the project, its functionality and design.

How to Play

Run the program to launch the bingo game window.

The screen displays two bingo cards: one for the player and one for the computer.

Press the space bar to draw a random number between 1 and 35.

The drawn number appears in the center of the screen.

If the number exists in either grid, it is crossed out automatically.

The program continuously checks whether any rows, columns, or diagonals are completed.

The first grid to complete five lines wins the game.

The program displays the winner through an animation before closing the game.

Game Interface

The graphical interface includes the following components:

A title displayed at the top of the screen.
Two bingo grids labeled Player and Computer.
A central display showing the most recently drawn number.
Counters that track the number of completed lines for each grid.
A visual animation that displays the final game result.

Key Functions in the Program

generate_card()
This function generates a 5 × 5 bingo card containing random numbers selected from the range 1 to 35 without duplication.

draw_grid()
This function draws the visual grid structure for the bingo cards using Turtle graphics.

write_numbers()
This function writes the generated numbers into the corresponding positions of the bingo grids.

draw_random_numbers()
This function is triggered when the space bar is pressed. It randomly selects a number, displays it on the screen, and checks both grids for matches.

check_bingo()
This function evaluates the bingo card to determine whether rows, columns, or diagonals have been fully completed.

game_over()
This function displays the final animation announcing the winner and closes the game window.

Features

The project provides a graphical bingo game implemented using Turtle graphics.
It generates randomized bingo cards for both the player and the computer.
Numbers are drawn interactively using keyboard input.
The program automatically marks numbers that appear on the cards.
Completed bingo lines are tracked and displayed in real time.
A final animation announces the game result.

Author

Sanjana
