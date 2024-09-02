# Labyrinth Game

Welcome to the Labyrinth Game! Navigate through the labyrinth, avoid bears, and find your way to the exit.

## Overview

This is a simple command-line game where you control a player in a labyrinth. You can move up, down, left, or right to navigate through the maze while avoiding bears.

## How to Play

1. **Commands**: 
   - Use `up` or `w` to move up
   - Use `down` or `s` to move down
   - Use `left` or `a` to move left
   - Use `right` or `d` to move right
   - Use `q` to quit the game

2. **Objective**: 
   - Navigate through the labyrinth.
   - Avoid bears.
   - Find the exit.

## Requirements

- Python 3.x
- pyfiglet

## Setup

1. Clone the repository:

    ```sh
    git clone <repository_url>
    ```

2. Install the required packages:

    ```sh
    pip install pyfiglet
    ```

3. Ensure the following files are in the correct directories:
    - `Player.py` in `impl/Player/`
    - `Labyrinth.py` in `impl/Labyrinth/`
    - `Bear.py` in `impl/Bear/`
    - `commands.py` in `impl/`
    - `Game.py` in the root directory or appropriate location

## Running the Game

1. Navigate to the directory containing the main script.
2. Run the game:

    ```sh
    python main.py
    ```

3. Follow the on-screen instructions to play the game.

## Game Structure

- `main.py`: The main entry point for the game.
- `impl/Player/Player.py`: Contains the Player class.
- `impl/Labyrinth/Labyrinth.py`: Contains the Labyrinth class.
- `impl/Bear/Bear.py`: Contains the Bear class.
- `impl/commands.py`: Contains the list of supported commands.
- `game.py`: Contains the Game class that integrates all components.

## Example Usage

```sh
$ python main.py

Labyrinth.....
The following commands are recognised:
up or w to move up
down or s to move down
left or a to move left
right or d to move right
Input a command
$> w
