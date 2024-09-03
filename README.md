# Design_1.5
## Description
Program to generate the shot and nodes postion and lines given a node polygon.
The shot polygon can be given but can also be computed by expanding the node polygon by a apron size.

## Inputs:

### 1- polipar1 

400 400 ----> Node X and Y space in m    
290000 490000 ----> Origin of the node grid   
0. ----> Node line direction  
30000 30000 ----> Length of the X and Y node grid  
200 200         ----> Pop space in m and Shot Line Space in m  
290000 490000   ----> Origin of the shot grid  
0. 8000.        ----> Shot line direction degrees and shot halo  
30000 30000     ----> Length of the X and Y shot grid  
Modelo PETROBRAS  
OPTION1 ESPG:NA  
0-degrees-SingleSource 12  
1 2   ------>   and  Number  of sources
4.6 .5     ---> speed source vessel in knots  and turn in hours
1. 3       ---->  ROV speed in knots and lines deployde before shooting
10 1000   ----> Record length (s) and approximate water depth im meters


### 2- pol2.txt    
x y  
300000 500000  
300000 508000  
308000 508000  
308000 500000  
300000 500000  

### 3- pol3.txt (Optional) Since you can expand the pol2.txt by a very smart function
x y  
292000 492000  
292000 516000  
316000 516000  
316000 492000  
292000 492000  


The output are: ( ALL INPUT in Map function and Folr Function)
1- shots.txt
2- nodes.txt
3- sail.txt
4- grid.txt

These files are input for map and fold programs

