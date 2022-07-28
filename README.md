# Binary-Search-Tree-Explanation

Suppose we have an array as [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

Here will be the order:
 - The root is 7;
 - 5 will be on the left side of root since it is lower than root;
 - 1 will be on the left of 5 since it is smaller than both;
 - 8 will be on the right side of the root since it is bigger than root;
 - 3 will be on the right side of 1
 - 6 will on the right side of 5
 - 0 will be on the left side of of 1
 - 9 will be on the right side of 8
 - 4 will be on the right side of 3
 - 2 will be on the left side of 3
 
Final result can be shown below: 
<
        7
       /  \
      5     8
     / \     \ 
    1   6      9
  /   \
 0      3
       /  \
      2     4
>
