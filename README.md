# leetcode_question

Given an m x n binary matrix mat, return the number of special positions in mat.

A position (i, j) is called special if mat[i][j] == 1 and all other elements in row i and column j are 0 (rows and columns are 0-indexed).

 

Example 1:


![image](https://github.com/SUSPECT007/leetcode_question/assets/103315098/a6200adb-d0f8-4a0f-b171-23e36e8f56cd)


Input: mat = [[1,0,0],[0,0,1],[1,0,0]]

Output: 1
Explanation: (1, 2) is a special position because mat[1][2] == 1 and all other elements in row 1 and column 2 are 0.

Example 2:


![image](https://github.com/SUSPECT007/leetcode_question/assets/103315098/a63b4470-a41c-4d27-90ab-4a8fd7ad65b7)




Input: mat = [[1,0,0],[0,1,0],[0,0,1]]


Output: 3



Explanation: (0, 0), (1, 1) and (2, 2) are special positions.


 

Constraints:

m == mat.length


n == mat[i].length


1 <= m, n <= 100


mat[i][j] is either 0 or 1.

https://leetcode.com/problems/special-positions-in-a-binary-matrix/description/?envType=daily-question&envId=2023-12-13

solve leetcode diary
__
