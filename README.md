Bingo Game Using Python Turtle

Player vs Computer Bingo Simulation

Overview

This project implements a graphical Bingo game using the Python Turtle graphics library. The game simulates a traditional bingo environment where a player competes against the computer using randomly generated bingo cards.

Both the player and the computer receive 5 × 5 bingo grids filled with numbers randomly selected from 1 to 35. During gameplay, random numbers are drawn and displayed on the screen. If the number appears in either grid, it is automatically crossed out.

The goal of the game is to complete five lines on a grid. A line can be:

A horizontal row

A vertical column

A diagonal

The first grid to complete five lines wins the game. If both grids complete the condition at the same time, the game ends in a tie.

The project demonstrates the use of Python graphics, event-driven programming, and game logic implementation.

Project Structure
├── bingo_game.py
├── README.md
Libraries Used
turtle
random

The Turtle library is included with the standard Python installation.

Game Interface

The graphical interface includes:

A title displayed at the top of the screen

Two bingo grids labeled Player and Computer

A central display showing the most recently drawn number

Counters that track the number of completed lines

A final animation that displays the game result

Bingo Card Generation

Each bingo card is generated using numbers between 1 and 35.

Characteristics of the bingo card:

Grid size: 5 × 5

Numbers are randomly arranged

No duplicate numbers appear in the same card

Example grid:

12   7   25   3   31
4    19  6    11  28
21   14  9    30  17
10   5   23   2   26
13   8   20   27  16
Game Logic

The game operates through the following steps:

Two bingo grids are created for the player and the computer.

The user presses the space bar to draw a random number.

The drawn number is displayed in the center of the screen.

If the number exists in a grid, it is marked with a cross.

The program checks whether any rows, columns, or diagonals are completed.

The counter showing completed lines is updated continuously.

The game ends when a grid completes five lines.

Possible outcomes:

Player wins

Computer wins

Tie

Key Functions in the Program
generate_card()

This function generates a 5 × 5 bingo card containing random numbers between 1 and 35 without duplication.

draw_grid()

This function draws the bingo grid structure on the screen using Turtle graphics.

write_numbers()

This function writes the generated numbers inside the corresponding grid cells.

draw_random_numbers()

This function draws a random number whenever the space bar is pressed, displays it on the screen, and checks whether it exists in either grid.

slash_number()

This function visually crosses out numbers that have already been drawn.

check_bingo()

This function checks whether the bingo card has completed any:

rows

columns

diagonals

It updates the line counter and determines whether the winning condition has been reached.

game_over()

This function displays the final animation announcing the winner and closes the game window.

Features

Graphical Bingo interface using Turtle graphics

Randomly generated bingo cards

Real-time number drawing and marking

Automatic detection of completed lines

Player vs Computer gameplay

Animated end-of-game display

Key Concepts Demonstrated

Python graphics programming

Event-driven programming

Random number generation

Game logic implementation

Grid-based visualization

Basic animation using Turtle graphics

Author

Sanjana

Python Programming Project
