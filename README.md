# CS50_AI_SixDegreesOfKevinBacon

## The implementation of Six Degrees of Bacon, with the help of BFS. 

First, We are defining the functions of finding the neighbours and with that, we are using the BFS Approach and Finding the shortest way of 
association between the two actors.

Eg: Let's say We want to find a connection between 'Tom Cruise'(A) and 'Jennifer Lawrence'(B). After running the algo, we find the neighbors
(the people that have worked with A) associated with both of them. After finding the neighbors, I am running a loop and finding if after 
traversing, we reach a point where one of the neighbours' state(or the Name of that actor) is equal to the target node. If so, then we are 
backtracking and finding the path. The path is returned as the shortest one.
