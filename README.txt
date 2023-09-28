Problem 1
 
Given two sets of elements, find the sum of all distinct elements from the set. In other words, find the sum of all elements which are present in either of the given set.
Example:
Set 1 : [3, 1, 7, 9], Set 2: [2, 4, 1, 9, 3]
Output: 13 (distinct elements 4, 7, 2 )
Give a solutions to this problem, using arrays


Problem 1
Solution  with an array.

Initialize sum = 0. 
Compare each element of set one with the second set and if element is not present then add that element to sum. 
Then do the vice versa to add elements from the second set.