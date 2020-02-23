Maze Roller

@author: Kodok-ki

Maze Roller is a simple game where a player rotates a maze with the WASD keys and guides a ball from the start point to the goal point.

The mechanics of the game are extremely simple but Maze Roller was developed with the intention of implementing a procedurally-generated maze. The specific algorithm used was depth-first search through a graph and its dual graph representing the walls and traversable space, respectively.

The current code allows for any square size with a simple change in variable, but there is not yet enough variance in the maze to justify playing larger mazes. The size shown in build 1.1 is simply what I decided to be optimal.

As of build 1.1, the maze comes in the form of a 2D (square) matrix but if I come back to this in the future, I hope to implement the maze-generation algorithm so that it accounts for different shapes, and accounts for different sizes by having more randomness in the maze paths.

Thank you for reading up to this point. I hope you enjoy Maze Roller.
