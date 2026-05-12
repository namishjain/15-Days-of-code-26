# 👋 Welcome to Vision CSE  

## Day 1
Solved LeetCode Problem No. 3925 - [Problem](https://leetcode.com/problems/concatenate-array-with-reverse/)

Solution: [Solution](https://leetcode.com/submissions/detail/1999438090/)

Logic: Iterated array from last index to first and simultaneously pushed it back into the original array

Solved CP31 Sheet Problems:

Problem: [1901/A](https://codeforces.com/problemset/problem/1901/A)

Solution: [1901/A](https://codeforces.com/problemset/submission/1901/374064555)

Logic: The initial fuel must be greater than the distance between any two fuel pumps and an exceptional case of twice of distance between second last and last fuel pump as refuelling is not allowed at the last fuel pump

Problem: [1900/A](https://codeforces.com/problemset/problem/1900/A)

Solution: [1900/A](https://codeforces.com/problemset/problem/1900/A)

Logic: Observation! If anywhere more than two empty cells are present, then the minmum number of type 1 actions required are two. Otherwise we check for the total number of appearance of empty cells which will give us the minimum number of type 1 actions

## Day 2
Solved LeetCode POTD - [Problem](https://leetcode.com/problems/separate-the-digits-in-an-array/description/?envType=daily-question&envId=2026-05-11)

Solution : [Solution](https://leetcode.com/submissions/detail/2000198432/)

Logic: Linearly iterate through the vector and at each index, convert the integer to string, then iterate over the string and convert each char into integer and push it into another vector

Spiral Traversal in a Binary Tree - [Problem](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)

Solution - [Solution](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/submissions/2000515095/)

Logic: Start from root node. Make two stacks s1(for left to right traversal) & s2 (for right to left traversal) across each level. Make a list in which we will store our answer for spiral traversal. Initially put root node in s1. while making s1 empty for each node, insert it's child nodes in stack s2. Repeat process with s2 and for each node in s2, insert it's child nodes in s1. While emptying respective stacks, insert the elements in the list. When both the stacks become empty, it means all levels are traversed and no other level is left to be traversed so simply return the list as our answer.

Solved CP31 Sheet Problems:

Problem: [1899/A](https://codeforces.com/contest/1899/problem/A)

Solution: [1899/A](https://codeforces.com/contest/1899/submission/374148446)

Logic: If number is divisible by 3, then Vanya would not be able to win as after chance of Vova the number will again become the same. Vanya can only win if the number is not divisble by 3.

Problem: [1896/A](https://codeforces.com/contest/1896/problem/A)

Solution: [1896/A](https://codeforces.com/contest/1896/submission/374149454)

Logic: Used a recursive approach. Find an element which is greater than the elements at previous and last index. Swap the index with it's next index till the list contains no such element and when it happens simply check if the list is sorted or not.

## Day 3

Tree Boundary Traversal - [Problem](https://www.geeksforgeeks.org/problems/boundary-traversal-of-binary-tree/1)

Solution - image in day3 folder

Logic: The problem can be broken down in three steps. First we will print out all the elements of the left boundary excluding the leaf nodes. In next step, we will print out all the leaf node elements and then we will print the element of right boundary but in reverse order. In this way we can print out all the nodes of tree by boundary traversal.

Solved CP31 Sheet Problem:

Problem: [1890/A](https://codeforces.com/contest/1890/problem/A)

Solution: [1890/A](https://codeforces.com/contest/1890/submission/374244712)

Logic: Observation! If there are more than 2 different elements present in the given array then it is not possible for array to become good. Then we will check if the only difference between the frequencies of only two numbers is <= 1. If the difference is <= 1 then it is possible for any permutation of array to become good, otherwise it is not possible
working or not