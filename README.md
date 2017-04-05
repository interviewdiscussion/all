# problem(locked)

## 156
[link](https://www.evernote.com/shard/s424/sh/00582161-4126-42c2-b911-3f11b053db07/c2a43009f62d9261bad9d23408fb8130)

## 157
[link](https://www.evernote.com/shard/s424/sh/469d7bec-e1b8-4e0d-ba2d-e0b2b2da0bab/03b32e7c4e879f677c522fd7847659cf)

## 158
[link](https://www.evernote.com/shard/s424/sh/b633abd1-58d6-4a7e-83f1-f9d4cbfd2c39/c94e58660128009d5bcbe1de37366db3)

## 159  
Given a string, find the length of the longest substring T that contains at most 2 distinct characters.  
For example, Given s = “eceba”,  
T is "ece" which its length is 3.  

## 161
Given two strings S and T, determine if they are both one edit distance apart.  

## 163  
Given a sorted integer array where the range of elements are in the inclusive range [lower, upper], return its missing ranges.  
For example, given [0, 1, 3, 50, 75], lower = 0 and upper = 99, return ["2", "4->49", "51->74", "76->99"].  


## 170  
Design and implement a TwoSum class. It should support the following operations: add and find.  

add - Add the number to an internal data structure.  
find - Find if there exists any pair of numbers which sum is equal to the value.  
For example,
```
add(1); add(3); add(5);
find(4) -> true
find(7) -> false
```
## 186  
Given an input string, reverse the string word by word. A word is defined as a sequence of non-space characters.  

The input string does not contain leading or trailing spaces and the words are always separated by a single space.  

For example,
```
Given s = "the sky is blue",
return "blue is sky the".
```
Could you do it in-place without allocating extra space?  

## 243  
Given a list of words and two words word1 and word2, return the shortest distance between these two words in the list.  

For example,
```
Assume that words = ["practice", "makes", "perfect", "coding", "makes"].
```
```
Given word1 = “coding”, word2 = “practice”, return 3.
Given word1 = "makes", word2 = "coding", return 1.
```

## 246  
A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).  

Write a function to determine if a number is strobogrammatic. The number is represented as a string.  

For example, the numbers "69", "88", and "818" are all strobogrammatic.  

## 247  
A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).  

Find all strobogrammatic numbers that are of length = n.  

For example,
```
Given n = 2, return ["11","69","88","96"].
```

## 249
Given a string, we can "shift" each of its letter to its successive letter, for example: "abc" -> "bcd". We can keep "shifting" which forms the sequence:  
```
"abc" -> "bcd" -> ... -> "xyz"
```
Given a list of strings which contains only lowercase alphabets, group all strings that belong to the same shifting sequence.  

For example, given: ```["abc", "bcd", "acef", "xyz", "az", "ba", "a", "z"]```, 
A solution is:  
```
[
  ["abc","bcd","xyz"],
  ["az","ba"],
  ["acef"],
  ["a","z"]
]
```

## 250  
Given a binary tree, count the number of uni-value subtrees.  

A Uni-value subtree means all nodes of the subtree have the same value.  

For example:  
Given binary tree,  
```
              5
             / \
            1   5
           / \   \
          5   5   5
```
return 4.

## 251  
Implement an iterator to flatten a 2d vector.

For example,
Given 2d vector =
```
[
  [1,2],
  [3],
  [4,5,6]
]
```
By calling next repeatedly until hasNext returns false, the order of elements returned by next should be: ```[1,2,3,4,5,6]```.

## 252  
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), determine if a person could attend all meetings.

For example,
```
Given [[0, 30],[5, 10],[15, 20]],
```
return false.

## 253
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), find the minimum number of conference rooms required.

For example,
```
Given [[0, 30],[5, 10],[15, 20]],
```
return 2.

## 254
Numbers can be regarded as product of its factors. For example,
```
8 = 2 x 2 x 2;
  = 2 x 4.
```
Write a function that takes an integer n and return all possible combinations of its factors.  

Note:  
You may assume that n is always positive.  
Factors should be greater than 1 and less than n.  
Examples:   
```
input: 1
output: 
[]
input: 37
output: 
[]
input: 12
output:
[
  [2, 6],
  [2, 2, 3],
  [3, 4]
]
input: 32
output:
[
  [2, 16],
  [2, 2, 8],
  [2, 2, 2, 4],
  [2, 2, 2, 2, 2],
  [2, 4, 4],
  [4, 8]
]
```
## 255  
Given an array of numbers, verify whether it is the correct preorder traversal sequence of a binary search tree.  

You may assume each number in the sequence is unique.  

Follow up:  
Could you do it using only constant space complexity?  

## 259
Given an array of n integers nums and a target, find the number of index triplets i, j, k with 0 <= i < j < k < n that satisfy the condition nums[i] + nums[j] + nums[k] < target.  

For example, given nums = [-2, 0, 1, 3], and target = 2.  

Return 2. Because there are two triplets which sums are less than 2:  
```
[-2, 0, 1]
[-2, 0, 3]
```

## 261  
Given n nodes labeled from 0 to n - 1 and a list of undirected edges (each edge is a pair of nodes), write a function to check whether these edges make up a valid tree.

For example:
```
Given n = 5 and edges = [[0, 1], [0, 2], [0, 3], [1, 4]], return true.
```
```
Given n = 5 and edges = [[0, 1], [1, 2], [2, 3], [1, 3], [1, 4]], return false.
```
## 266  
Given a string, determine if a permutation of the string could form a palindrome.  

For example,  
```
"code" -> False, "aab" -> True, "carerac" -> True.
```
## 267

Given a string s, return all the palindromic permutations (without duplicates) of it. Return an empty list if no palindromic permutation could be form.  

For example:  
```
Given s = "aabb", return ["abba", "baab"].
```
```
Given s = "abc", return [].
```

## 270  
Given a non-empty binary search tree and a target value, find the value in the BST that is closest to the target.  

Note:  
Given target value is a floating point.  
You are guaranteed to have only one unique value in the BST that is closest to the target.  

## 276  
There is a fence with n posts, each post can be painted with one of the k colors.  

You have to paint all the posts such that no more than two adjacent fence posts have the same color.  

Return the total number of ways you can paint the fence.  

Note:  
n and k are non-negative integers.  

## 280  
Given an unsorted array nums, reorder it in-place such that nums[0] <= nums[1] >= nums[2] <= nums[3]....  

For example, given nums = [3, 5, 2, 1, 6, 4], one possible answer is [1, 6, 2, 5, 3, 4].  



## 285  
Given a binary search tree and a node in it, find the in-order successor of that node in the BST.  

Note: If the given node has no in-order successor in the tree, return null.  




## 298
Given a binary tree, find the length of the longest consecutive sequence path.  

The path refers to any sequence of nodes from some starting node to any node in the tree along the parent-child connections. The longest consecutive path need to be from parent to child (cannot be the reverse).  

For example,
```
   1
    \
     3
    / \
   2   4
        \
         5
```
Longest consecutive sequence path is 3-4-5, so return 3.
```
   2
    \
     3
    / 
   2    
  / 
 1
```
Longest consecutive sequence path is 2-3,not3-2-1, so return 2.



## 302
An image is represented by a binary matrix with 0 as a white pixel and 1 as a black pixel. The black pixels are connected, i.e., there is only one black region. Pixels are connected horizontally and vertically. Given the location (x, y) of one of the black pixels, return the area of the smallest (axis-aligned) rectangle that encloses all black pixels.  

For example, given the following image:  
```
[
  "0010",
  "0110",
  "0100"
]
```
and ```x = 0, y = 2```,
Return ```6```.

## 311
Given two sparse matrices A and B, return the result of AB.  

You may assume that A's column number is equal to B's row number.  

Example:  
```
A = [
  [ 1, 0, 0],
  [-1, 0, 3]
]

B = [
  [ 7, 0, 0 ],
  [ 0, 0, 0 ],
  [ 0, 0, 1 ]
]


     |  1 0 0 |   | 7 0 0 |   |  7 0 0 |
AB = | -1 0 3 | x | 0 0 0 | = | -7 0 3 |
                  | 0 0 1 |
```



## 314  
Given a binary tree, return the vertical order traversal of its nodes' values. (ie, from top to bottom, column by column).  

If two nodes are in the same row and column, the order should be from left to right.  

Example:  
Given binary tree [3,9,20,null,null,15,7],  
```
   3
  /\
 /  \
 9  20
    /\
   /  \
  15   7
```
return its vertical order traversal as:  
```
[
  [9],
  [3,15],
  [20],
  [7]
]
```
Given binary tree [3,9,8,4,0,1,7],
```
     3
    /\
   /  \
   9   8
  /\  /\
 /  \/  \
 4  01   7
```
return its vertical order traversal as:
```
[
  [4],
  [9],
  [3,0,1],
  [8],
  [7]
]
```
Given binary tree [3,9,8,4,0,1,7,null,null,null,2,5] (0's right child is 2 and 1's left child is 5),
```
     3
    /\
   /  \
   9   8
  /\  /\
 /  \/  \
 4  01   7
    /\
   /  \
   5   2
```
return its vertical order traversal as:
```
[
  [4],
  [9,5],
  [3,0,1],
  [8,2],
  [7]
]
```




## 320  
Write a function to generate the generalized abbreviations of a word.  

Example:  
Given word = "word", return the following list (order does not matter):  
```
["word", "1ord", "w1rd", "wo1d", "wor1", "2rd", "w2d", "wo2", "1o1d", "1or1", "w1r1", "1o2", "2r1", "3d", "w3", "4"]
```

## 339  
Given a nested list of integers, return the sum of all integers in the list weighted by their depth.  

Each element is either an integer, or a list -- whose elements may also be integers or other lists.  

Example 1:
```
Given the list [[1,1],2,[1,1]], return 10. (four 1's at depth 2, one 2 at depth 1)
```
Example 2:
```
Given the list [1,[4,[6]]], return 27. (one 1 at depth 1, one 4 at depth 2, and one 6 at depth 3; 1 + 4*2 + 6*3 = 27)
```

## 340  
Given a string, find the length of the longest substring T that contains at most k distinct characters.  

For example, Given s = “eceba” and k = 2,  

T is "ece" which its length is 3.  


## 346  
Given a stream of integers and a window size, calculate the moving average of all integers in the sliding window.

For example,
```
MovingAverage m = new MovingAverage(3);
m.next(1) = 1
m.next(10) = (1 + 10) / 2
m.next(3) = (1 + 10 + 3) / 3
m.next(5) = (10 + 3 + 5) / 3
```


## 356  
Given n points on a 2D plane, find if there is such a line parallel to y-axis that reflect the given points.  

Example 1:
```
Given points = [[1,1],[-1,1]], return true.
```
Example 2:
```
Given points = [[1,1],[-1,-1]], return false.
```
## 360  
Given a sorted array of integers nums and integer values a, b and c. Apply a function of the form f(x) = ax2 + bx + c to each element x in the array.  

The returned array must be in sorted order.  

Expected time complexity: O(n)  

Example:
```
nums = [-4, -2, 2, 4], a = 1, b = 3, c = 5,

Result: [3, 9, 15, 33]

nums = [-4, -2, 2, 4], a = -1, b = 3, c = 5

Result: [-23, -5, 1, 7]
```
## 369  
Given a non-negative integer represented as non-empty a singly linked list of digits, plus one to the integer.  

You may assume the integer do not contain any leading zero, except the number 0 itself.  

The digits are stored such that the most significant digit is at the head of the list.  

Example:
```
Input:
1->2->3

Output:
1->2->4
```

## 548  
[link](https://www.evernote.com/shard/s424/sh/bf2b11d4-33e4-4a06-b2c2-8ef3cad0fdce/c30a120ae663f7fbeb1c5af1c14e0aa1)
