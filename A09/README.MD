dfs explaination 
After readGraph has read in the input. dfs details with the matrix. 
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

0 0 0 0r

0 1 1 1

If the neighbor is within the matrix bounds and has not been visited (DFS_WHITE), a recursive call to dfs is made with the new coordinates.
The matrix is is iterated through the top, bottom and diagonal parts of the matrix (as described in the code comments).
