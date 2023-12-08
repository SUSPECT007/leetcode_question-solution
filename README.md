# leetcode_question

Given the root of a binary tree, construct a string consisting of parenthesis and integers from a binary tree with the preorder traversal way, and return it.

Omit all the empty parenthesis pairs that do not affect the one-to-one mapping relationship between the string and the original binary tree.

 

Example 1:

![image](https://github.com/SUSPECT007/leetcode_question/assets/103315098/8f317cb1-d18f-4528-b8e6-ff92cca26b51)


Input: root = [1,2,3,4]

Output: "1(2(4))(3)"

Explanation: Originally, it needs to be "1(2(4)())(3()())", but you need to omit all the unnecessary empty parenthesis pairs. And it will be "1(2(4))(3)"


Example 2:


![image](https://github.com/SUSPECT007/leetcode_question/assets/103315098/70ca6c08-8c5a-4030-bf80-71f752d64d49)



Input: root = [1,2,3,null,4]

Output: "1(2()(4))(3)"


Explanation: Almost the same as the first example, except we cannot omit the first parenthesis pair to break the one-to-one mapping relationship between the input and the output.
 

Constraints:


The number of nodes in the tree is in the range [1, 104].

https://leetcode.com/problems/construct-string-from-binary-tree/?envType=daily-question&envId=2023-12-08

solve leetcode diary
__
