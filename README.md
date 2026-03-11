# Bingo Game Using Python Turtle

## Overview

This project implements a **graphical Bingo game** using the **Python programming language** and the **Turtle graphics library**. The game simulates a traditional bingo environment in which a **player competes against the computer** using randomly generated bingo cards.

Both the player and the computer receive **5 × 5 bingo grids** containing numbers randomly selected from **1 to 35**. During gameplay, numbers are drawn randomly and displayed on the screen. If a drawn number appears in either grid, it is **automatically crossed out**.

The objective of the game is to complete **five lines** on a grid. A line may be a **row, column, or diagonal**. The first grid to complete **five lines** wins the game. If both grids reach this condition simultaneously, the game ends in a **tie**.

The graphical interface displays the **bingo cards, drawn numbers, and completed line counters** for both the player and the computer.

---

## Project Structure

```
bingo-game/
│
├── bingo_game.py
├── README.md
```

---

## Libraries Used

The project uses the following Python libraries:

**turtle** – Used to create the graphical interface and draw the bingo grids.  
**random** – Used to generate random numbers for the bingo cards and number draws.

The **Turtle library** is included in the **standard Python installation**, so no additional installation is required.

---

## Game Interface

The graphical interface contains several elements that allow the user to visually follow the progress of the game.

The interface includes:

- A **BINGO title** displayed at the top of the screen  
- Two **5 × 5 bingo grids** labeled **Player** and **Computer**  
- A central display showing the **most recently drawn number**  
- **Counters** that track the number of completed lines for each grid  
- A **final animation** that displays the winner of the game  

---

## Bingo Card Generation

Each bingo card is generated using numbers in the range **1 to 35**.

Characteristics of the bingo card include:

- **Grid size:** 5 × 5  
- **Random arrangement of numbers**  
- **No duplicate numbers** within the same card  

Example structure of a bingo card:

```
12   7   25   3   31
4    19  6    11  28
21   14  9    30  17
10   5   23   2   26
13   8   20   27  16
```

---

## Game Logic

The game operates through a sequence of steps that simulate the process of a bingo draw.

1. Two bingo grids are generated for the **player** and the **computer**.
2. The user presses the **space bar** to draw a random number.
3. The drawn number is displayed in the **center of the screen**.
4. If the number appears on either grid, it is **crossed out automatically**.
5. The program continuously checks for completed **rows, columns, and diagonals**.
6. A counter updates the number of **completed lines** for each grid.
7. The game ends when a grid completes **five lines**.

Possible outcomes include:

- **Player wins**
- **Computer wins**
- **Tie**

---

## Key Functions in the Program

**generate_card()**  
Generates a **5 × 5 bingo card** containing randomly selected numbers between **1 and 35** without duplication.

**draw_grid()**  
Draws the **bingo grid structure** on the screen using Turtle graphics.

**write_numbers()**  
Writes the generated numbers inside the corresponding cells of the bingo grid.

**draw_random_numbers()**  
Triggers when the **space bar** is pressed. It draws a random number, displays it on the screen, and checks both grids for matches.

**slash_number()**  
Visually **crosses out numbers** that have been drawn.

**check_bingo()**  
Checks whether the bingo card has completed any **rows, columns, or diagonals**, updates the counter, and determines whether the winning condition has been reached.

**game_over()**  
Displays the **final animation announcing the winner** and closes the game window.

---

## Features

The project includes several features that demonstrate graphical programming and interactive gameplay:

- **Graphical Bingo interface** built using Turtle graphics  
- **Randomly generated bingo cards** for both player and computer  
- **Real-time number drawing and marking**  
- Automatic detection of **completed rows, columns, and diagonals**  
- **Player vs Computer gameplay**  
- **Animated end-of-game display**

---

## Key Concepts Demonstrated

This project demonstrates several important programming concepts, including:

- **Python graphics programming**
- **Event-driven programming**
- **Random number generation**
- **Game logic implementation**
- **Grid-based visualization**
- **Basic animation using Turtle graphics**

---

## Author

**Sanjana**

Python Programming Project
