# leetcode_question

Given head, the head of a linked list, determine if the linked list has a cycle in it.

There is a cycle in a linked list if there is some node in the list that can be reached again by continuously following the next pointer. Internally, pos is used to denote the index of the node that tail's next pointer is connected to. Note that pos is not passed as a parameter.

Return true if there is a cycle in the linked list. Otherwise, return false.

 

Example 1:


![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/5537e90a-7ce9-49cb-a293-f58d038ef658)



Input: head = [3,2,0,-4], pos = 1

Output: true

Explanation: There is a cycle in the linked list, where the tail connects to the 1st node (0-indexed).



Example 2:

![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/82248741-be9c-4ff4-a512-cebf0789b369)


Input: head = [1,2], pos = 0

Output: true

Explanation: There is a cycle in the linked list, where the tail connects to the 0th node.


Example 3:

![image](https://github.com/SUSPECT007/leetcode_question-solution/assets/103315098/07b9ec17-a07f-4939-9dae-a9bc94d679da)


Input: head = [1], pos = -1

Output: false

Explanation: There is no cycle in the linked list.


-


 

Constraints:

The number of the nodes in the list is in the range [0, 104].

-105 <= Node.val <= 105

pos is -1 or a valid index in the linked-list.


https://leetcode.com/problems/linked-list-cycle/description/?envType=daily-question&envId=2024-03-06

solve leetcode diary
__
