# This folder contains the solution for the Seasonal War Problem
## Approach:
To solve this problem you must first understand how the "dfs" function works. 

The "dfs" function explaination:

After "readGraph" function has read in the input. dfs deals with the matrix. 
After matrix is made, the index for matrix array is checked to verify a "node" has been visited (0) or not (1). 
For example:

1 0 0 1

1 1 0 0

0 0 1 0

0 1 1 1

the function would begin at (0,0) marking all non visited nodes (or all 1) to visited (or 0)
eventually based on the node you are looking for all of them would be 0. For this example if you are looking for 
(3,3) the matrix would look like 

0 0 0 0

0 0 0 0

0 0 0 0

0 1 1 1

If the neighbor is within the matrix bounds and has not been visited (DFS_WHITE), a recursive call to dfs is made with the new coordinates.

The matrix is is iterated through the top, bottom and diagonal parts of the matrix (as described in the code comments).

To solve the Seasonal War problem the ones (1) in the image must not touch each other, or have any adject ones next to it. At that point it is considered a war eagle. 
## Thoughs:
I didn't write this. Source is [here]().......

There were too many components to account for, it was difficult to even under the code. Not only did you had to check if the nodes were visited or not but you also had to find out whether there is an eagle to the left, right, top or bottom of another. This would cause condition after condition to develop. Hence the multitude of "if" statements. 

|   #   | File |  Description |
| :---: | ----------- | ---------------------- |
|  1 | [Main](https://github.com/azizzmills/Programming-Techniques/blob/2143-OOP-Mills/A09/code) | Main driver of my program which solves problem. |
|  2 | [Input]() | Input |
|  3 | [PDF](https://github.com/azizzmills/Programming-Techniques/blob/2143-OOP-Mills/A09/p352.pdf) | Problem statement and guidelines  |



