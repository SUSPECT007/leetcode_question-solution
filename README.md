# leetcode_question

1319. Number of Operations to Make Network Connected

There are n computers numbered from 0 to n - 1 connected by ethernet cables connections forming a network where connections[i] = [ai, bi] represents a connection between computers ai and bi. Any computer can reach any other computer directly or indirectly through the network.

You are given an initial computer network connections. You can extract certain cables between two directly connected computers, and place them between any pair of disconnected computers to make them directly connected.

Return the minimum number of times you need to do this in order to make all the computers connected. If it is not possible, return -1.

 ![image](https://user-images.githubusercontent.com/103315098/227155938-04e51e11-6845-47c6-bfd1-a52b9806436d.png)

Constraints:

1 <= n <= 105

1 <= connections.length <= min(n * (n - 1) / 2, 105)

connections[i].length == 2

0 <= ai, bi < n

ai != bi

There are no repeated connections.

No two computers are connected by more than one cable.

https://leetcode.com/problems/number-of-operations-to-make-network-connected/description/

solve leetcode diary
__
