# Maze
a simple 3D OpenGL game
## Specifications: ##
* Solves the maze tree with iteration method and makes the path green
* Program runs up to 1500x1500+ maze (around 4.500.000 blocks)
* Detects whether if you solve the maze
* Maze generator algorithm from: https://github.com/norvig/pytudes/blob/master/ipynb/Maze.ipynb
## Dependencies: ##
* [GLFW](https://www.glfw.org "GLFW")
* [GLEW](http://glew.sourceforge.net "GLEW")
* [stb_image](https://github.com/nothings/stb/blob/master/stb_image.h "stb_image")
* [glm](https://github.com/g-truc/glm "glm")
## Run: ##
Create a file named libraries and copy dependencies into it. Click solution (if needed, change solution platform) and run.
## Control: ##
* Press 'C' for cheat mode on/off
* if cheat mode is on, use arrow keys for speed up or down and also do not affect restarting (stay same position)
* Press 'E' for escape path on/off
* Press 'R' for restart, generates new maze and camera goes default starting point
