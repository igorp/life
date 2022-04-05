Game of Life
====

Conway's Game of Life is a cellular automaton created by John Conway in 1970. Basically its a kind of a simulation of how a grid of squares evolves and changes with time. Each square on the grid changes its state from dead to alive
depending on the previous state. Here are the rules:

1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overcrowding.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

As for the implementation itself, there is a two-dimensional array of Booleans in which the cells are stored as either dead or alive. Then we loop as many times as we want checking the next state. It is important to first make a copy of the original grid and not directly change the grid, because this will mess everything up. Finally you must not forget to set the initial state, so that there is something to begin with.

For more information on the subject check out the wikipedia article: http://en.wikipedia.org/wiki/Conway's_Game_of_Life
