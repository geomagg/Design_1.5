# Design_1.5
Initial upload

Program to generate the shot and nodes postion and lines given a node polygon.
The shot polygon can be given but can also be computed by expanding the node polygon by a apron size.

The file polypar 1 tells :

400 400         ----> Node X and Y space in m  
290000 490000   ----> Origin of the node grid 
0.              ----> Node line direction
30000 30000     ----> Length of the X and Y node grid
200 200         ----> Pop space in m and Shot Line Space in m
290000 490000   ----> Origin of the shot grid
0. 8000.        ----> Shot line direction degrees and shot halo
30000 30000     ----> Length of the X and Y shot grid
Modelo PETROBRAS
OPTION1 ESPG:NA
0-degrees-SingleSource 12
1 2


The output are:
1- shots.txt
2-nodes.txt
3- sail.txt
4- grid.txt

These files are input for map and fold programs

