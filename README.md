Snake Game

This project implements a simple snake game using Python's turtle graphics module and freegames utilities. The snake moves around the screen, growing longer as it eats food, and the game ends if the snake collides with itself or goes out of bounds.

Features

Interactive Gameplay: Use arrow keys to control the snake's movement (Up, Down, Left, Right).

Dynamic Difficulty: The game speeds up as the snake grows longer.

Randomized Food: Food appears at random positions on the screen.

Collision Detection: Game over when the snake hits the wall or itself.

Prerequisites

Ensure you have Python installed with the following modules:

turtle (Standard Library)

random (Standard Library)

freegames (Install via pip if not already available)

Installation

Install Python: Download Python

Install the freegames module by running:

pip install freegames

How to Run

Save the provided code into a file named snake_game.py.

Open a terminal or command prompt and navigate to the file's directory.

Run the script using:

python snake_game.py

Control the snake with the arrow keys.

Controls

Key

Action

Up

Move the snake upwards

Down

Move the snake downwards

Left

Turn the snake left

Right

Turn the snake right

Code Overview

Main Components

Game Variables:

food: A red square representing food for the snake.

snake: A list of vectors representing the snake's body.

aim: A vector that determines the snake's movement direction.

Functions:

change(x, y): Updates the snake's direction based on user input.

inside(head): Checks if the snake's head is within game boundaries.

move(): Handles the movement of the snake, collision detection, and food consumption.

Event Listeners:

Arrow key events (onkey) to control the snake's direction.

Game Loop:

The move function is repeatedly called using ontimer to animate the game.

Known Limitations

No pause or restart functionality.

The game window is fixed at a size of 400x400 pixels.

Future Improvements

Add a scoring system displayed on the screen.

Implement different levels of difficulty.

Add a start and pause menu.

Sample Gameplay

The snake starts with one segment.

Use the arrow keys to collect red squares (food).

Avoid hitting walls or the snake's own body.

The game ends when a collision occurs.

Enjoy the game!

