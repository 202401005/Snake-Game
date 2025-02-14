# Snake Game in C++

This is a simple **Snake Game** implemented in **C++**, which runs in the console. The player controls the snake to eat food (#) while avoiding collisions with walls or itself.

## How to Play

- Use the WASD keys to move the snake:
  - W → Move Up
  - S → Move Down
  - A → Move Left
  - D → Move Right
- Press X to exit the game.
- The game ends if the snake collides with the wall or its own body.

## Features

- Player Name Input: The game asks for the player's name before starting.
- Score Tracking: The score increases by 10 for each food item eaten.
- Snake Tail Growth: The snake gets longer after eating food.
- Difficulty Levels:
  - Easy (1) → Slow speed
  - Medium (2) → Default speed
  - Hard (3) → Fast speed

## Prerequisites

To run the game, you need:
- A C++ compiler (e.g., G++, MinGW, or MSVC)
- Windows OS (since the game uses <conio.h> and windows.h)

## How to Compile and Run

1. Open a terminal or command prompt.
2. Compile the program using:
   ```sh
   g++ snake_game.cpp -o snake_game.exe
