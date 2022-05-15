# Insertion Sort Project
## [22,27,16,2,18,6] 
## 1. Write the steps of above list based on its sort type.
(Algorithm runs up to case that testing element is greater than element which is just before it.)
1. First check 22 ; 22 is sorted itself , so 1st step:  [22,27,16,2,18,6]

2. Then, check 27 , 27>22 , so 2nd step:  [22,27,16,2,18,6]

3. Then, check 16 , 16<27 so swap them & 16<22 so swap them,  3rd step: [16,22,27,2,18,6] 

4. Then, check 2 , 2<27 so swap them & 2<22 so swap them & 2<16 so swap them,  4th step: [2,16,22,27,18,6]

5. Then, check 18 , 18<27 so swap them & 18<22 so swap them   5th step: [2,16,18,22,27,6]

6. Then, check 6 , 6<27 so swap them & 6<22 so swap them & 6<18 so swap them & 6<16 so swap them,  6th step: [2,6,16,18,22,27]
## 2.Big-O Notation
- There is a descending step size from n to 1, so total step size can be described as [n*(n+1)]/2 and n^2 has dominant behaviour. 
-  Big-O Notation is O(n^2)
## 3.Time Complexity
- Worst Case: The case that reversed order array. So, time complexity n^2
- Best Case : The self ordered array case. Time complexity n
- Average Case: Average of best and worse case. So, time complexity n^2
## 4.What is the case of 18 after sorting?
Since it is in the middle of the array, it is in average case.
## 5. [7,3,5,8,2,9,4,15,6] First 4 steps of given array based on insertion sort
(Algorithm runs up to case that testing element is greater than element which is just before it.)
1. First check 7 ; 7 is sorted itself , so 1st step:  [7,3,5,8,2,9,4,15,6]

2. Then, check 3 , 3<7 , so swap them, 2nd step:  [3,7,5,8,2,9,4,15,6]

3. Then, check 5 , 5<7 so swap them,  3rd step: [3,5,7,8,2,9,4,15,6] 

4. Then, check 8 , 8>7  4th step: [3,5,7,8,2,9,4,15,6]

