# Simple Cricket Game 🏏

## Overview
This is a simple C program that simulates a one-over (6 balls) cricket match between the user and the computer. The game involves batting and bowling phases, where the user and the computer take turns. The winner is determined based on the scores after both phases.

## Features
- **Interactive Gameplay**: User inputs their runs and bowling choices.
- **Randomized Computer Moves**: The computer generates random inputs for batting and bowling.
- **Dynamic Scoring**: Scores are updated and displayed after every ball.
- **Match Rules**: 
  - A player is "OUT" if the batting number matches the bowling number.
  - The match ends early if the computer surpasses the user's score during its batting phase.
- **Winner Declaration**: Announces the match result with final scores.

## How to Play
1. Enter a number between 1 and 6 for each ball during your batting or bowling phase.
2. Avoid invalid inputs (outside the range 1-6), or you will be prompted to re-enter.
3. If the batting number matches the bowler's number, the batter is "OUT."
4. The game ends after 6 balls or earlier if the batter is out or the computer chases the target score.

## Gameplay Example
### Game Start

## Compilation and Execution
1. Save the program to a file named `cricket_game.c`.
2. Open a terminal and compile the program using GCC:
   ```bash
   gcc cricket_game.c -o cricket_game
