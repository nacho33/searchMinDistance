### Search minimum distance between two consecutive numbers

The task consists on calculating the minimum distance between two consecutive numbers in an array. 

Some considerations:
 - If we have [1,4] the consecutive number of 1 is 4. In this case it's only 1 position, so the result is 1. 
 - If we have only the same value in the array [3,3] we should return -1
 - If we have [1,4,4,1,5,2], the previous and the following values for 4 are 2 and 5, not the other 4.
 

For example we have the following array
[1,4,7,3,3,5]
 - The following value of 1 is the 3, the distance is 3 positions.
 - With the 4 the distance with the 3 (previous value in order) is 2 and it's going to be the minimum. 
