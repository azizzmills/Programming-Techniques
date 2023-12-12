# This folder contains the solution for the Commandos Problem
## Approach:
The point of this program was to find the time taken to the shortest path to the enemy base. First thing that was needed to be done was to building the graph. Afetr the buildings and its neigbours are intialized, each building is visited going deeper and deeper into the "tree". Until the required building is found. A queue is used to keep track of the order of the buildings that are visited. The distance is tracked from the intial building to the building of interest. Since one time unit moved is equaled to visiting a building, the total time will be tallied at the end. The program will end when all possible paths are explored.
## Thoughs:
### I didnt write this code. The source is [here](https://github.com/SaruarChy/Uva-Online-judge-Solution/blob/master/11463%20-%20Commandos.cpp).......
But it was interesting. The use of the for loops were very in genius to go deeper and deeper in the graph minicking the transverasal through a tree. 

|   #   | File |  Description |
| :---: | ----------- | ---------------------- |
|  1 | [Main]() | Main driver of my program which solves problem. |
|  2 | [Input]( ) | Input |
|  3 | [PDF]( ) | Problem statement and guidelines  |
