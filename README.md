Turtle Game
=========

Introduction
------------

Welcome to Turtle Game, a simple game where you control a turtle to cross a road filled with cars. The goal is to cross the road without getting hit by a car. The game keeps track of your score and levels up as you successfully cross the road.

Files
-----

1. **main.py**: The main entry point of the game. It imports the necessary modules and starts the game loop.
2. **turtle.py**: A module that defines a Turtle class for creating turtle objects. It includes methods for moving the turtle and updating its position.
3. **car_manager.py**: A module that defines a CarManager class for creating and managing cars on the road. It includes methods for creating cars, moving them, and checking for collisions with the turtle.
4. **scoreboard.py**: A module that defines a Scoreboard class for keeping track of the player's score and high score. It includes methods for increasing the score and displaying the high score.

Game Loop
---------

The game loop consists of the following steps:

1. Initialize the game by creating a Turtle object and a CarManager object.
2. Start the game loop by calling the `game_loop()` function in `main.py`.
3. In the game loop, check for user input (e.g., arrow keys for moving the turtle).
4. Update the turtle's position based on user input.
5. Check for collisions between the turtle and cars.
6. If a collision occurs, end the game and display the final score.
7. Otherwise, move the cars and update their positions.
8. Check for leveling up and update the score accordingly.
9. Render the game board with the turtle and cars.
10. Repeat steps 3-9 until the game ends.

Game Mechanics
-------------

The game mechanics are as follows:

1. The turtle can move up using the arrow keys.
2. The turtle can only move when it is not colliding with a car.
3. Cars move automatically.
4. If a car collides with the turtle, the game ends, and the final score is displayed.
5. The player earns points for successfully crossing the road without getting hit by a car.
6. The game levels up when the player successfully crosses the road, and the speed of the cars increases.

Installation
------------

To install the game, simply clone the repository and run `python main.py` in the terminal.

License
-------

The game is licensed under the MIT License.

Acknowledgments
---------------

Thanks to the following people for their contributions to the game:
Angela Yu
