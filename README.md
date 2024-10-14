# 2048 Game Recreation in Python

## Project Overview
This project is a Python recreation of the popular **2048 game**, originally developed by Gabriele Cirulli in 2014. The objective of the game is simple yet challenging: combine tiles on a 4x4 grid to create a tile with the value **2048**. Players control the movement of the tiles using the commands `W`, `A`, `S`, and `D` (for up, left, down, and right respectively). Each move shifts the tiles as far as possible in the selected direction, merging tiles with the same value. The game ends when no further moves can be made or the 2048 tile is created.

This project is built with Python's core functionality, and optionally, a graphical interface can be implemented using libraries like **Tkinter** or **Pygame**.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Game](#running-the-game)
- [Game Rules](#game-rules)
- [Controls](#controls)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Core 2048 Mechanics**: Sliding, merging, and tile generation following standard 2048 rules.
- **Random Tile Generation**: New tiles with values of `2` or `4` are added after each move.
- **Game Over Detection**: The game ends when the grid is full and no valid moves can be made.
- **Win Condition**: The game is won when the player reaches the 2048 tile.
- **Text-based UI**: A simple text-based interface that prints the grid and accepts user inputs.

## Getting Started

### Prerequisites
Before you can run the game, you’ll need the following:
- Python 3.x
- Optional: Libraries like **Tkinter** or **Pygame** if you wish to implement a graphical user interface (GUI).

### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/2048-game-python.git
   
2. **Navigate to the Project Directory**:
   ```bash
   cd 2048-game-python
3. **Install Required Libraries** (optional for GUI):
   If you plan to use a graphical interface, install the required libraries:
   ```bash
   pip install tkinter pygame
4. **Run the Game**:
   Start the game in your terminal by running:
   ```bash
   python 2048.py
## Game Rules
1. **Objective**: The goal of the game is to combine tiles on a 4x4 grid to create a tile with the value **2048**.
  
2. **Grid Setup**: The game starts with two tiles on the grid, typically with values of **2** or **4**.

3. **Movement**: Players can move the tiles in four directions:
   - **Up (`W` or `w`)**: Move all tiles up.
   - **Down (`S` or `s`)**: Move all tiles down.
   - **Left (`A` or `a`)**: Move all tiles left.
   - **Right (`D` or `d`)**: Move all tiles right.

4. **Merging Tiles**: 
   - When two tiles with the same number touch, they merge into one tile, and their values are added together (e.g., two tiles with **2** merge to form a tile with **4**).
   - A tile can only merge once per move.

5. **Tile Generation**: After each move, a new tile with a value of **2** or **4** will randomly appear in an empty spot on the grid.

6. **Game Over**: The game ends when:
   - The grid is full and no more valid moves are possible.
   - A tile with the value **2048** is created.

7. **Winning the Game**: Although the game can continue beyond creating the 2048 tile, the primary objective is to achieve this milestone.

8. **Scoring**: The score increases with each tile merger, reflecting the sum of the merged tiles.

### File Descriptions
- **2048.py**: The main script that runs the game, implementing the game logic, user input handling, and rendering the game state.
- **README.md**: Documentation file providing an overview of the project, instructions for installation, and rules of the game.
- **requirements.txt**: A file listing any additional Python libraries that need to be installed (if applicable).
- **assets/**: A directory that may contain graphical assets for a GUI version of the game (optional).
