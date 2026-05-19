# 👋 Welcome to Vision CSE  

## Day 1
* Solved LeetCode Problem No. 3925 - [Problem](https://leetcode.com/problems/concatenate-array-with-reverse/)

Solution: [Solution](https://leetcode.com/submissions/detail/1999438090/)

Logic: Iterated array from last index to first and simultaneously pushed it back into the original array

Solved CP31 Sheet Problems:

* Problem: [1901/A](https://codeforces.com/problemset/problem/1901/A)

Solution: [1901/A](https://codeforces.com/problemset/submission/1901/374064555)

Logic: The initial fuel must be greater than the distance between any two fuel pumps and an exceptional case of twice of distance between second last and last fuel pump as refuelling is not allowed at the last fuel pump

* Problem: [1900/A](https://codeforces.com/problemset/problem/1900/A)

Solution: [1900/A](https://codeforces.com/problemset/problem/1900/A)

Logic: Observation! If anywhere more than two empty cells are present, then the minmum number of type 1 actions required are two. Otherwise we check for the total number of appearance of empty cells which will give us the minimum number of type 1 actions

## Day 2
* Solved LeetCode POTD - [Problem](https://leetcode.com/problems/separate-the-digits-in-an-array/description/?envType=daily-question&envId=2026-05-11)

Solution : [Solution](https://leetcode.com/submissions/detail/2000198432/)

Logic: Linearly iterate through the vector and at each index, convert the integer to string, then iterate over the string and convert each char into integer and push it into another vector

* Spiral Traversal in a Binary Tree - [Problem](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)

Solution - [Solution](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/submissions/2000515095/)

Logic: Start from root node. Make two stacks s1(for left to right traversal) & s2 (for right to left traversal) across each level. Make a list in which we will store our answer for spiral traversal. Initially put root node in s1. while making s1 empty for each node, insert it's child nodes in stack s2. Repeat process with s2 and for each node in s2, insert it's child nodes in s1. While emptying respective stacks, insert the elements in the list. When both the stacks become empty, it means all levels are traversed and no other level is left to be traversed so simply return the list as our answer.

Solved CP31 Sheet Problems:

* Problem: [1899/A](https://codeforces.com/contest/1899/problem/A)

Solution: [1899/A](https://codeforces.com/contest/1899/submission/374148446)

Logic: If number is divisible by 3, then Vanya would not be able to win as after chance of Vova the number will again become the same. Vanya can only win if the number is not divisble by 3.

* Problem: [1896/A](https://codeforces.com/contest/1896/problem/A)

Solution: [1896/A](https://codeforces.com/contest/1896/submission/374149454)

Logic: Used a recursive approach. Find an element which is greater than the elements at previous and last index. Swap the index with it's next index till the list contains no such element and when it happens simply check if the list is sorted or not.

## Day 3

* Tree Boundary Traversal - [Problem](https://www.geeksforgeeks.org/problems/boundary-traversal-of-binary-tree/1)

Solution - image in day3 folder

Logic: The problem can be broken down in three steps. First we will print out all the elements of the left boundary excluding the leaf nodes. In next step, we will print out all the leaf node elements and then we will print the element of right boundary but in reverse order. In this way we can print out all the nodes of tree by boundary traversal.

Solved CP31 Sheet Problem:

* Problem: [1890/A](https://codeforces.com/contest/1890/problem/A)

Solution: [1890/A](https://codeforces.com/contest/1890/submission/374244712)

Logic: Observation! If there are more than 2 different elements present in the given array then it is not possible for array to become good. Then we will check if the only difference between the frequencies of only two numbers is <= 1. If the difference is <= 1 then it is possible for any permutation of array to become good, otherwise it is not possible

## Day 4

* Right Side View of a Binary Tree - [Problem](https://leetcode.com/problems/binary-tree-right-side-view/)

Solution - [Solution](https://leetcode.com/problems/binary-tree-right-side-view/submissions/2001832847/)

Logic: We will use a map (to fetch only one value from each level) and an array (to store our answer). To print right side view of a binary tree, we will start traversing towards the right pushing values in array and indexing tha each level of tree so that when we will traverse towards the left we will not push the values back in the array

Solved CP31 Sheet Problems:

* Problem: [1881/A](https://codeforces.com/contest/1881/problem/A)

Solution [1881/A](https://codeforces.com/contest/1881/submission/374345820)

Logic: By given constraints we can observe that if x is duplicated by 5 times and till that if s is found to be a substring of x then we will break at that instant and answer will be the number of times x was duplicated & if not possible then answer will be -1

* Problem: [1878/A](https://codeforces.com/contest/1878/problem/A)

Solution: [1878/A](https://codeforces.com/contest/1878/submission/374346367)

Logic: Check if k is present in the array or not

* Problem: [1877/A](https://codeforces.com/contest/1877/problem/A)

Solution: [1877/A](https://codeforces.com/contest/1877/submission/374346514)

Logic: Simply return the negative of the sum of the array

## Day 5

* LeetCode POTD: [Problem](https://leetcode.com/problems/check-if-array-is-good/?envType=daily-question&envId=2026-05-14)

Solution: [Solution](https://leetcode.com/submissions/detail/2002637517/)

Logic: Use Hashmap and store the frequency of each element in an array. Now iterate through the array and check if all elements other than n occur once and n occur twice. if that's not the case return false otherwise return true

* Symmetric Binary Tree: [Problem](https://leetcode.com/problems/symmetric-tree/)

Solution: [Solution](https://leetcode.com/submissions/detail/2002742488/)

Logic: We will use two seperate traversals, one to the left and one to the right. make two stacks s1 and s2. when traversing to the left subtree go from left child to right child for each node and store the elements in s1. While traversing to the right subtree go from right child to the left child for each node and store the elements in s2. After traversing, remove elements from both the stack simultaneously. The top element in both the stacks should be equal for binary tree to be symmetric

Solved CP31 Sheet Problems:

* Problem: [1873/C](https://codeforces.com/problemset/problem/1873/C)

Solution: [1873/C](https://codeforces.com/problemset/submission/1873/374457341)

Logic: Create a score matrix according to the problem. Now iterate through each charachter of each string present. When the char is equal to X append the value at that index of matrix.

* Problem: [1866/A](https://codeforces.com/problemset/problem/1866/A)

Solution: [1866/A](https://codeforces.com/problemset/submission/1866/374458176)

Logic: Return the minimum absolute value from the elements provided possible

## Day 6

* Binary Tree Paths: [Problem](https://www.geeksforgeeks.org/problems/root-to-leaf-paths/1)

Solution: in image of day6 folder

Logic: Start traversing from the root node to the left pushing elements in a vector. When we reach final child node then push the vector into ans vector and pop the last element from vector v. Continue same while traversing to the right

Solved CP31 Sheet Problems:

* Problem: [1862/B](https://codeforces.com/contest/1862/problem/B)

Solution: [1862/B](https://codeforces.com/contest/1862/submission/374562137)

Logic: For each value in the given vector b, if the current element in greater than previous element then insert it into a otherwise insert it twice in the vector a

## Day 7

Solved LeetCode POTD: [Problem](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/?envType=daily-question&envId=2026-05-16)

Solution: [Solution](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/submissions/2004304144/?envType=daily-question&envId=2026-05-16)

Logic: Standard Binary Search Solution. Solved previously from Striver's Sheet of finding minimum in a rotated sorted array with duplicates

Solved CP31 Sheet Problems:

Problem: [1859/A](https://codeforces.com/contest/1859/problem/A)

Solution: [1859/A](https://codeforces.com/contest/1859/submission/374676928)

Logic: Put all the largest elements of array in the second array and the remaining elements in the first array. If size of first array becomes zero then it is not possible to construct the given two arrays, otherwise it is possible and print the sizes and the elements of the two arrays respectively

Problem: [1858/A](https://codeforces.com/contest/1858/problem/A)

Solution: [1858/A](https://codeforces.com/contest/1858/submission/374678039)

Logic: First assign all the c buttons to both Anna and Katie and then check whether a > b or b > a according to the given conditions and return the answer accordingly

## Day 8

Maximum Width of a Tree: [Problem](https://www.geeksforgeeks.org/problems/maximum-width-of-tree/1)

Solution: in img of day8 folder

Logic: Traverse through each level of the tree and store the frequency of elements in a map. Then find the maximum value for all the keys of the map

Solved Contest Problem 3931: [Problem](https://leetcode.com/problems/check-adjacent-digit-differences/)

Solution: [Solution](https://leetcode.com/submissions/detail/2005407930/)

Logic: Linearly iterate through the string and check the difference between the two adjacent charachters and find the difference. If the difference between the 2 is greater then 2 then return false otherwise return true at the end of loop.

Solved CP31 Sheet Problems:

Problem: [1857/A](https://codeforces.com/problemset/problem/1857/A)

Solution: [1857/A](https://codeforces.com/problemset/submission/1857/374924037)

Logic: Calculate the sum of all the odd elements and even elements separately and check the parity of both. if parity of the both the sum is same then return true otherwise return false

Problem: [1853/A](https://codeforces.com/problemset/problem/1853/A)

Solution: [1853/A](https://codeforces.com/problemset/submission/1853/374925850)

Logic: If array is unsorted return 0. Otherwise check for minimum difference between two consecutive elements are return minDiff/2 + 1.

## Day 9

Children Sum Property in a Binary Tree: [Problem](https://www.geeksforgeeks.org/problems/children-sum-parent/1)

Solution: img in day9 folder

Logic: Check the sum of left and right child for each node. if the sum equals to the value of parent node then return true otherwise return false

Count Complete Tree Nodes: [Problem](https://leetcode.com/problems/count-complete-tree-nodes/)

Solution: [Solution](https://leetcode.com/submissions/detail/2006278120/)

Logic: If the current node is not null then simply count it as one node. Then traverse through the left and right of the current node and return the total number of nodes.

Solved CP31 Sheet Problems:

Problem: [1845/A](https://codeforces.com/contest/1845/problem/A)

Solution: [1845/A](https://codeforces.com/contest/1845/submission/375014689)

Logic: Count the occurence of even and odd elements and then apply conditions according to the problem

Problem: [1837/A](https://codeforces.com/contest/1837/problem/A)

Solution: [1837/A](https://codeforces.com/contest/1837/submission/375047783)

Logic: Just check if x is divisble by k or not.

## Day 10

Solved LeetCode POTD: [Problem](https://leetcode.com/problems/minimum-common-value/)

Solution: [Solution](https://leetcode.com/submissions/detail/2006928902/)

Logic: Store the values of first array in a map and find the minimum during iteration in the second array

Burning Tree Problem: [Problem](https://leetcode.com/problems/amount-of-time-for-binary-tree-to-be-infected/)

Solution: [Solution](https://leetcode.com/submissions/detail/2007135048/)

Solved CP31 Sheet Problems:

Problem: [1834/A](https://codeforces.com/contest/1834/problem/A)

Solution: [1834/A](https://codeforces.com/contest/1834/submission/375186702)

Logic: Check the occurrence of 1 and -1. The number of operations will be equal to the all the -1 converted to 1 to make them less than the no. of 1. After that if the no. of -1 present is not is divisible by 2 then operations will be incremented by 1

Problem: [1831/A](https://codeforces.com/contest/1831/problem/A)

Solution: [1831/A](https://codeforces.com/contest/1831/submission/375188873)

Logic: Each element of b will be equal to n + 1 - ai so that the sum of ai + bi across all i will be equal
