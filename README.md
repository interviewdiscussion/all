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

## 244
[link](https://www.evernote.com/shard/s424/sh/b3a16113-c926-4f8d-bab6-040eba4e8493/0b8ab7a3670a79074c5b022c83a8533c)

## 245
[link](https://www.evernote.com/shard/s424/sh/dd5c5f2b-913a-45ed-9d48-da5ad544aa7f/0c40b3b31b8881d2e1b389992b65813f)


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
## 248  
[link](https://www.evernote.com/shard/s424/sh/cbd0f673-bb41-49c0-92d6-e0750c33da46/9b5eebf05afe16320b0a1962e9a336f6)

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

## 256  
[link](https://www.evernote.com/shard/s424/sh/e3d5dce9-ca85-4943-b390-b2266724ecb5/b567d0e0597a6a83d69b0f5caf137e1d)

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


## 265  
[link](https://www.evernote.com/shard/s424/sh/206176a4-ab13-4324-be46-f7bf7c7571e3/1206c2895f2ed8d0ab093752ff0a6c7a)

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

## 269
[link](https://www.evernote.com/shard/s424/sh/636f555a-0bed-4451-8937-207411a6245e/d35bbaf99b4c63e5a971f3b2c901c815)


## 270  
Given a non-empty binary search tree and a target value, find the value in the BST that is closest to the target.  

Note:  
Given target value is a floating point.  
You are guaranteed to have only one unique value in the BST that is closest to the target.  

## 271
[link](https://www.evernote.com/shard/s424/sh/319287ee-1bca-4f30-b2e2-621bb8b4102d/adbc40221698ce47c97c70f09950e0ba)

## 272
[link](https://www.evernote.com/shard/s424/sh/adc2a62a-c674-439f-b472-83e2a0b45db4/a7e6144d2290f9d164ee3b41baeac7d9)  



## 276  
There is a fence with n posts, each post can be painted with one of the k colors.  

You have to paint all the posts such that no more than two adjacent fence posts have the same color.  

Return the total number of ways you can paint the fence.  

Note:  
n and k are non-negative integers.  

## 277
[link](https://www.evernote.com/shard/s424/sh/d521ebde-5640-4b6a-9670-912fcfd807ae/08ef95ec398086aec4db93b860b7a5cf)



## 280  
Given an unsorted array nums, reorder it in-place such that nums[0] <= nums[1] >= nums[2] <= nums[3]....  

For example, given nums = [3, 5, 2, 1, 6, 4], one possible answer is [1, 6, 2, 5, 3, 4].  

## 281
[link](https://www.evernote.com/shard/s424/sh/a211d171-2190-4139-bf91-81629f4ae212/ee5c86760956168af57372bec2623ebb)




## 285  
Given a binary search tree and a node in it, find the in-order successor of that node in the BST.  

Note: If the given node has no in-order successor in the tree, return null.  

## 286
[link](https://www.evernote.com/shard/s424/sh/33347f6a-613d-4af6-8610-edd14b3e3869/9c2d0c9c4b58d00423ccd51161f00164)


## 288
[link](https://www.evernote.com/shard/s424/sh/b4b87cc8-5dc9-4f12-bf6b-7ac9b80475ad/e285230c7cb3c22b8f27046cbd2e5c66)

## 291
[link](https://www.evernote.com/shard/s424/sh/b4e05817-60d1-49f5-8abb-8889db2fce56/514a840255ba8bdcf196c082290131a8)


## 293  
[link](https://www.evernote.com/shard/s424/sh/928d885c-af24-44b8-b12c-2911769b6ce9/c7202c18fc20c4204698d1c653dda0ea)

## 294  
[link](https://www.evernote.com/shard/s424/sh/68d026fe-f62b-494f-bbd4-84ca39f650f2/35b39963b5da845faa993a302014ac44)  

## 296
[link](https://www.evernote.com/shard/s424/sh/1c5be68a-63d1-4d5c-ae1d-8950f1b3a34c/fc3bb126fcd582123cb196f8670a4518)  


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

## 305  
[link](https://www.evernote.com/shard/s424/sh/ed79eb47-1d64-4063-ab24-73b19f54bf9a/13c84b992f2cb37320e367fc2f232435)


## 308
[link](https://www.evernote.com/shard/s424/sh/5948b5ce-9da6-4479-8e86-1cdcaed6f5f4/5c55bb988a51c7f0581a7e160086dcaf)


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

## 317  
[link](https://www.evernote.com/shard/s424/sh/b586853d-5528-44bf-a691-7bedbe1d0e14/239cdcb3518f0feaf9814bc49575ccbf)




## 320  
Write a function to generate the generalized abbreviations of a word.  

Example:  
Given word = "word", return the following list (order does not matter):  
```
["word", "1ord", "w1rd", "wo1d", "wor1", "2rd", "w2d", "wo2", "1o1d", "1or1", "w1r1", "1o2", "2r1", "3d", "w3", "4"]
```


## 323
[link](https://www.evernote.com/shard/s424/sh/38719821-f35b-444a-8bfb-2e393c9c8eea/e2126d374ef3269cd70cf338696b116c)  


## 325
[link](https://www.evernote.com/shard/s424/sh/a9c3d83e-cfa2-4b07-881e-c2acfa6db4bd/2bc587aab8c4f64c54bf00b56938c526)

## 333
[link](https://www.evernote.com/shard/s424/sh/33b7e93f-0416-4dc5-ba37-026f174e1870/5ea219baa539b220ffa110868079e07c)  


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
## 348  
[link](https://www.evernote.com/shard/s424/sh/9b27d847-189a-41cf-9ce0-f94e9cdb2286/52b8251785312e1781c7217575a33d34)

## 351
[link](https://www.evernote.com/shard/s424/sh/7fa4958e-abbd-4ad6-ad85-1d479b0995b9/01b9e69bd42f2a394eb85bd6b60edad7)

## 353
[link](https://www.evernote.com/shard/s424/sh/cffd88c1-9dcf-4b5a-b828-2c081fe7a6bf/b154dda9aebfa6303e6aa9e09c8a95df)



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

## 358  
[link](https://www.evernote.com/shard/s424/sh/044b487b-a6a8-41ef-acdc-af5c55e8b755/8553ad10d919c0410e801431ec4d8669)

## 359
[link](https://www.evernote.com/shard/s424/sh/9a4e8e77-6fc7-4100-ad2a-bfaad527f9c7/82d1b472ca1e513fca50c5e37bd45792)


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

## 361
[link](https://www.evernote.com/shard/s424/sh/5184b861-970f-44dc-a123-dc58e4bd6023/d144dc20fe5644e7cde83c26c1e0062b)

## 362
[link](https://www.evernote.com/shard/s424/sh/ae3ef874-1fdf-4e73-9af1-cad1764c49d0/422c5f7c14d9866793014ad1e10d6a4a)


## 364
[link](https://www.evernote.com/shard/s424/sh/71e1c141-fbb0-4836-80d9-dcd18a7b0672/3feda6c830c8c7c853f51b118005af91)

## 366
[link](https://www.evernote.com/shard/s424/sh/b28fe7b1-7768-460f-b7d7-45f07748dd42/9770f2d7a40fbeef4b3bf6bd3723d34a)

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

## 370
[link](https://www.evernote.com/shard/s424/sh/601ce4c1-c010-4787-9401-879fcbf6decf/9b662193ea8685003f3fc634380a2038)

## 379
[link](https://www.evernote.com/shard/s424/sh/d4833cd1-7790-4071-b83a-09fcbc68b192/ec2aa43c39ecc5255c7c3497b7aebf04)

## 408
[link](https://www.evernote.com/shard/s424/sh/f9d3e066-8436-4b6d-9810-912c2134be03/8e6453dd17abc2b3553a1d6c7625b655)

## 411
[link](https://www.evernote.com/shard/s424/sh/17ac6efa-664a-43f9-a3c3-154fed9d3eac/dd6fa86f13c9d4f3ec2eae71400424eb)

## 418
[link](https://www.evernote.com/shard/s424/sh/ed137749-7d7e-4fe9-8711-a1074bf4ded7/b5372605046ab1a486b06c0ce67754af)

## 422
[link](https://www.evernote.com/shard/s424/sh/6bdba465-22e1-4a25-9bee-479104b0e9c5/3adb808ed811e18cffd5435a94049d8a)

## 425
[link](https://www.evernote.com/shard/s424/sh/e7b4a78e-9a19-4553-9795-7db8d4927a22/912144d1ec229cf0ed7fba23cf4b877b)

## 439
[link](https://www.evernote.com/shard/s424/sh/2060a367-6988-4b07-b7d8-0a5c3f697bf0/4516b842fa67175339facb4d35605d4e)

## 444
[link](https://www.evernote.com/shard/s424/sh/70a768de-a551-4b8b-90fb-e78c184f05f9/c4986c92d10f73e48626dad1bffc97da)

## 465
[link](https://www.evernote.com/shard/s424/sh/9d347619-3ab9-4840-a339-ef036fce8f9e/71db497c7511466e40cde522876ecb77)

## 469
[link](https://www.evernote.com/shard/s424/sh/ed293415-0128-4d5f-be5d-b95ff98eb151/df1a6771318eef1693276d23c7d0a66a)

## 471
[link](https://www.evernote.com/shard/s424/sh/3211ccec-f1c8-4447-8b15-b6fa5b54e8e0/781414b935e33d2e8820c6aa61c7a210)

## 484
[link](https://www.evernote.com/shard/s424/sh/220c5e8e-8a71-4da0-89cb-f45ab99e7e25/fdaf9ac2578c5cceaa18318181902505)

## 487
[link](https://www.evernote.com/shard/s424/sh/1334618b-64a2-4a82-806f-17510567ad3e/f114a5b1e47957ffd0fe93628112a035)

## 490
[link](https://www.evernote.com/shard/s424/sh/2c941797-cafc-42fe-a4d6-3e37eb301f17/64ec70e6567c7d847807621a8c98a241)

## 499
[link](https://www.evernote.com/shard/s424/sh/7e20f3d4-a5bf-4bb3-bdc7-1757f7d8ce56/8e20cf58f5b4522499ddb9aa952465ed)

## 505
[link](https://www.evernote.com/shard/s424/sh/53234af7-bb87-434a-803e-f7e2d3cbd73a/4aa33b96d3498b72d6ab76a8a98bfa86)

## 527
[link](https://www.evernote.com/shard/s424/sh/032c81ef-344c-466c-b01a-7d680ae0f4ec/45d67e1a8aee0f0fd704e3f57f3da98d)

## 531
[link](https://www.evernote.com/shard/s424/sh/59109a8c-3334-46a7-9e23-dd0e29f480c4/60904e89b1f442411594491f9cc306be)

## 533
[link](https://www.evernote.com/shard/s424/sh/7e8a40eb-b831-4487-b11f-cdfac63c1366/2e535063492544ce9072ae44573caf47)

## 536
[link](https://www.evernote.com/shard/s424/sh/4152fe9f-b417-4ccb-b6c1-141aa3f90821/4436ab01fbfe4a2c162da93b3d4e3e69)

## 544
[link](https://www.evernote.com/shard/s424/sh/d917007c-d6b9-4272-a1e1-6ba6cf96e0d4/d141ed294fcbfcc5e4cd25cd13dd2636)

## 545
[link](https://www.evernote.com/shard/s424/sh/fef0c1d8-b135-4795-9a0a-68b124f5c9c1/1f3446a74a7a9cc6e3435afe9f5ec321)

## 548  
[link](https://www.evernote.com/shard/s424/sh/bf2b11d4-33e4-4a06-b2c2-8ef3cad0fdce/c30a120ae663f7fbeb1c5af1c14e0aa1)

## 549
[link](https://www.evernote.com/shard/s424/sh/217ca5b4-2af2-4c1f-a5d4-f1ce095a3950/87bc4452d990a7a467e2731233c5502b)

## 555
[link](https://www.evernote.com/shard/s424/sh/75afb910-9591-4464-94b8-3afcc7e79766/68d5b882595055adb21b5a72a3c57e6f)

## 562
Given a 01 matrix M, find the longest line of consecutive one in the matrix. The line could be horizontal, vertical, diagonal or anti-diagonal.  

Example
```
Input:
[[0,1,1,0],
 [0,1,1,0],
 [0,0,0,1]]
Output: 3
```

## 568
[link](https://www.evernote.com/shard/s424/sh/c8cdb40c-cbb3-4f20-9d2a-2283e86e8f23/2b7080848c3dc2ffbcc483d0e1538507)

## 569
[link](https://www.evernote.com/shard/s424/sh/c0db943e-30e5-4442-94ee-8ef1a415204f/a6191ad097bfc11f51edde01fd786e63)

## 570
[link](https://www.evernote.com/shard/s424/sh/2710cdad-22e5-4cb7-83e5-4a57e34dc36f/0d9ec8cf02a0c9a324ba772041067638)

## 573
[link](https://www.evernote.com/shard/s424/sh/54dfccee-aa99-4e09-a0b7-6ad43e103786/aa5b0dcbb09b2b6cc3b3aeb4f83651a1)

## 574
[link](https://www.evernote.com/shard/s424/sh/f5e8b9f2-ed2b-4033-b7da-7fe560e27986/830c5ba880ebf228e632d1477201fff8)

## 577
[link](https://www.evernote.com/shard/s424/sh/3cd5c85e-ebf7-404b-b54a-14ec88ca6380/bca6ec6e4e659d7ed8b58df2c8e9ee71)

## 579
[link](https://www.evernote.com/shard/s424/sh/b4ef789b-42c0-4266-a3a4-821e0eef533e/e3a2588891337e0f834882413803de14)
