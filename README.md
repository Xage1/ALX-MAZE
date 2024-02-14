This is the 3D MAZE in relation to the required Project for the ALX SE Programme.


This 3D maze uses raycasting to draw the maze walls, utilizing LodeV's method of using vectors to calculate ray length. By default the maze uses textures but textures can be disabled on execution.

Controls
W : move forward
S : move backward
A : rotate camera left
D : rotate camera right
Q : strafe left
E : strafe right
F : toggle fullscreen
ESC : quit


There are 3 maps to choose from, The maps are defined in 2D arrays in text files, which are parsed when passed as an argument to the maze executable. 0 represents open space, all other integers are drawn as walls.
