# data-structure-algorithms
Data Structure and Algorithms
Insertion Sort Project
[22,27,16,2,18,6] -> Insertion Sort

Steps:
[22,27,16,2,18,6] => n
[2,27,16,22,18,6] => n-1
[2,6,16,22,18,27] => n-2
[2,6,16,18,22,27] => 1

Big-O show: n(n+1)/2 O(n^2)

Time Complexity: Average case: Middle number,
Worst case: last number, 
Best case: first number in array.

18 is in middle so it is in "Average Case"
[7,3,5,8,2,9,4,15,6] arrays firs 4 steps regards with Insertion Sort

Steps:
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]


Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

         [16,21,11]      [8,12,22]
       [16] [21,11]       [8] [12,22]
     [16]  [21]  [11]   [8]  [12]    [22]
      [16,21]     [8,11]       [12,22]
         [8,11,16,21]    [12,22]
            [8,11,12,16,21,22]
            
    Big-O showcase >> O(nlogn)
