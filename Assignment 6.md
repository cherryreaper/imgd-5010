# Game of Life

### Link

[p5js Game of Life](https://editor.p5js.org/cherryreaper/sketches/iygr02Urg)

## Decription
This version of the game of life uses the class of cells to store the curretn and previous states of the cell. 
It starts by creating an empty 2D array and then filling it with Cells with a state of either 1 or 0 (which is also assigned to previous)

Upon start, the program iterates through the grid using a nested for loop. 
A second nested for loop is used to test the Cell's neighbors (skipping itself), and adding 1 if the neighbor is alive.
Afterwards, it can calculate what to do next based on the number of neighbors, according to the rules of the game of life. 

The Cell then assigned it's current state as "previous" for it's next runthrough.
