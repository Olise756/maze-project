# The Maze

The Maze is a 3D Maze game that uses ray casting to render a 2D map into a 3D navigable world!

The Maze was written was written in C ussing SDL2 library.

## Usage 
* Execute ./maze or type make run 
* Use up and down arrow keys to move forward and backward (keys w and s serve the same function)
* Use right and left arrow keys to turn the camera arround (keys d and a serve the same function)

## Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`;
```