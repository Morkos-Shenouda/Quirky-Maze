Overview
This project is an interactive maze game built with Python and Pygame, using a quantum-inspired random number generator to add unpredictability. Players navigate a maze with the goal of "catching" a moving button to claim their reward. The maze is generated using a unique traversal method that differs from traditional algorithms like BFS or DFS, providing a fresh and challenging experience.

Key Features
Unique Maze Generation: The maze is generated with an innovative traversal algorithm, offering a distinctive structure and pathing from standard BFS or DFS-based mazes.
Quantum Randomness: Quantum-inspired randomness via Qiskit determines the button's unpredictable movements.
Moving Button Challenge: Players must catch a randomly moving button, adding a layer of excitement and difficulty.
Password-Protected Rewards: After catching the button, players enter a password to claim a virtual pile of chocolates.
Smooth Visual Effects: The background smoothly transitions colors, creating an engaging visual experience.
___________________________________________________________________________________________________________________________________________________________________________________________________________________
Requirements
Python: Ensure Python 3.x is installed.
Pygame: Required for graphics and game interactions.
Qiskit: Provides quantum-inspired randomness for the game.
Installing Required Libraries
Install dependencies via pip:

pip install pygame qiskit

___________________________________________________________________________________________________________________________________________________________________________________________________________________
How to Play
Run the main game file QuantumMazeGame.py.
Navigate the Maze: Use the arrow keys to move through the maze, which has been generated with a new traversal method.
Catch the Moving Button: Find and click the "Claim" button that moves around randomly within the maze.
Claim Your Reward: After catching the button, enter the correct password to claim the chocolate reward. There is a limit to the number of attempts.
Enjoy the Visuals: Experience the smooth color transitions as you play.
___________________________________________________________________________________________________________________________________________________________________________________________________________________
Files
QuantumMazeGame.py: The main game script, containing the maze generation, game loop, and all functions.
README.md: Instructions and details (this file).
___________________________________________________________________________________________________________________________________________________________________________________________________________________
Functions and Classes
generate_maze(sc)
Generates the maze using a novel traversal algorithm that is neither BFS nor DFS, resulting in unique paths and structures.

run_button_catch_game(sc)
Initializes and runs the game loop, incorporating the maze, button movement, and player interactions.

check_password(correct_password, num_of_chocolates, max_attempts=10)
Manages password entry and displays feedback. A congratulatory message is shown if the password is correct.

changeColor(slowness)
Smoothly transitions the background color between a specified range, enhancing the game’s visual appeal.

Cell
Represents each cell in the maze grid, manages wall properties, and handles drawing the cell using Pygame.

Dependencies
Pygame: For graphics, player controls, and maze rendering.
Qiskit: Quantum-inspired randomness for the button’s unpredictable movement.
___________________________________________________________________________________________________________________________________________________________________________________________________________________
License
This project is open-source and licensed under the MIT License.

