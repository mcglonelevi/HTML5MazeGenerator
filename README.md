# HTML5MazeGenerator
Maze Generator with Javascript, a seedable RNG, and HTML5 Canvas

I used this PRNG - https://github.com/skeeto/rng-js

My goal with this project was to make a seedable maze generator.  Unlike most maze generators, my maze uses "blocks" instead of walls to divide the maze.  I did this, because I intend to use this algorithm in a Minecraft-like game where walls are not an option.

Feel free to edit my code.  If you have a game engine, you could rip out all of the display code and use the basic array that is generated.  0's represent walls and 1's represent spaces.

I like the way that the code functions.  I may eventually turn this into a better library.

At the moment, the maze starts at [1,1], but you could set this position randomly.
