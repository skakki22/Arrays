# Arrays
Problems we solved for this Data Structure 

<b>1. Maximum Subarray (picked up from leetcode)</b>

Given an integer array nums, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.

Example:

Input: [-2,1,-3,4,-1,2,1,-5,4], Output: 6 Explanation: [4,-1,2,1] has the largest sum = 6. Follow up:

If you have figured out the O(n) solution, try coding another solution using the divide and conquer approach, which is more subtle.

<b>2. Rotate Array: </b>

Given an unsorted array arr[] of size N, rotate it by D elements (clockwise).

Input: The first line of the input contains T denoting the number of testcases. First line of each test case contains two space separated elements, N denoting the size of the array and an integer D denoting the number size of the rotation. Subsequent line will be the N space separated array elements.

Output: For each testcase, in a new line, output the rotated array.

Constraints: 1 <= T <= 200 1 <= N <= 107 1 <= D <= N 0 <= arr[i] <= 105

Example: Input: 2 5 2 1 2 3 4 5 10 3 2 4 6 8 10 12 14 16 18 20

Output: 3 4 5 1 2 8 10 12 14 16 18 20 2 4 6

Explanation : Testcase 1: 1 2 3 4 5 when rotated by 2 elements, it becomes 3 4 5 1 2.

<b>3. K-diff Pairs in an Array</b>

Given an array of integers and an integer k, you need to find the number of unique k-diff pairs in the array. Here a k-diff pair is defined as an integer pair (i, j), where i and j are both numbers in the array and their absolute difference is k.

Example 1:
Input: [3, 1, 4, 1, 5], k = 2
Output: 2

Explanation: There are two 2-diff pairs in the array, (1, 3) and (3, 5).

Although we have two 1s in the input, we should only return the number of unique pairs.

Example 2:

Input:[1, 2, 3, 4, 5], k = 1

Output: 4

Explanation: There are four 1-diff pairs in the array, (1, 2), (2, 3), (3, 4) and (4, 5).

Example 3:

Input: [1, 3, 1, 5, 4], k = 0

Output: 1

Explanation: There is one 0-diff pair in the array, (1, 1).

Note:
The pairs (i, j) and (j, i) count as the same pair.

The length of the array won't exceed 10,000.

All the integers in the given input belong to the range: [-1e7, 1e7].


<b>4. Merge Sorted Array:</b>

Given two sorted integer arrays nums1 and nums2, merge nums2 into nums1 as one sorted array.

Note:

The number of elements initialized in nums1 and nums2 are m and n respectively.
You may assume that nums1 has enough space (size that is equal to m + n) to hold additional elements from nums2.

Example:

Input:
nums1 = [1,2,3,0,0,0], m = 3
nums2 = [2,5,6],       n = 3

Output: [1,2,2,3,5,6]
 

Constraints:

-10^9 <= nums1[i], nums2[i] <= 10^9
nums1.length == m + n
nums2.length == n

<b>5. Given an array of integers, find if the array contains any duplicates. </b>

Your function should return true if any value appears at least twice in the array, and it should return false if every element is distinct.

Example 1:

Input: [1,2,3,1]
Output: true
Example 2:

Input: [1,2,3,4]
Output: false
Example 3:

Input: [1,1,1,3,3,4,3,2,4,2]
Output: true
