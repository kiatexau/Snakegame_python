This is a simple Snake game implemented in Python using the turtle library for the graphical user interface. 
The game offers a classic Snake experience where the player controls a snake to collect food items and grow longer. 
The objective is to collect as many points as possible before colliding with the walls or the snake's own body.

Core Functionality: The code implements the basic Snake game logic: snake movement, food consumption, growth, and collision detection.
Libraries: It uses the turtle module for graphics, time for delays, and random for food placement.
Game Mechanics:
The snake moves in discrete steps.
Food is placed randomly on the screen.
The snake grows by one segment each time it eats food.
The game ends when the snake collides with the border or itself.
User Interface:
The game window is created using turtle.Screen().
The snake, food, and score are drawn using turtle.Turtle() objects.
Keyboard input is used for snake control.
