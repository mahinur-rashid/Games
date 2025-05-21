# Tetris Game

A classic Tetris game implementation using Python and Pygame.

## Features

- Classic Tetris gameplay mechanics
- Score tracking and best score retention
- Time tracking and longest time played recording
- Animated menu interfaces
- Next block preview
- Instructions screen

## Controls

- Left Arrow: Move block left
- Right Arrow: Move block right
- Up Arrow: Rotate block
- Down Arrow: Soft drop (faster fall)
- Space: Hard drop (immediate fall)

## Requirements

- Python 3.x
- Pygame library

## Installation

1. Make sure you have Python installed on your system
2. Install Pygame using pip:
   ```
   pip install pygame
   ```
3. Clone or download the repository

## Project Structure

- `tetris.py` - Main game logic and UI management
- `util.py` - Utility classes and functions including:
  - Block management
  - Playing field
  - Button system
  - Color definitions
  - Game constants

## How to Run

Navigate to the project directory and run:
```
python tetris.py
```

## Game Features

- Multiple block shapes (I, L, J, O, S, T, Z blocks)
- Score system based on completed rows
- Time tracking
- Animated menus and transitions
- Best score and longest time tracking
- Grid-based playing field
- Preview window for next block
