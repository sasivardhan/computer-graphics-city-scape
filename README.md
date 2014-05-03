computer-graphics-city-scape
============================

OpenGL to write a complete program that generates a picture of a 7‐day forecast for a major city.   The program should first  input 7 numbers from the user
  These numbers represent the highest 
temperatures forecast for the city for each of the next 7 days.   After the numbers are input, the 
program should generate a graph illustrating the change in temperatures over the next 7 days and 
draw it over a skyline for the city. 
 
The graph may be a line graph of a bar graph, but it must be generated using the primitives discussed 
in  class (points, lines, polygons).   You may not use a pre‐existing package or function specifically 
designed for drawing graphs.  The color of the lines or bars of the graph must be different from the 
color used in drawing the city skyline (discussed next). 
 
The  city skyline  needs to  contain  buildings  with  different  heights  and shapes.    In  addition, the 
buildings in the skyline need to have visible windows.  Again, the entire skyline must be generated 
using the primitives discussed in class. 


Perform the following stepsin orderto addGLUT to your Visual Studio 2012 project
environment. 
 
1. Unzip GLUT and copy its contents to a directory of your choosing (say C:\glut) 
2. Right click on Project (“Sample”) in Solution Explorer and Select Properties 
3. Select Configuration Properties in the left pane 
4. Add the glut directory you chose in Step 1 to the Executable Directories, Include 
Directories, Reference Directories, and Library Directories 
5. Include “glut.h” in your C++ code 
 
