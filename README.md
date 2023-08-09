# 2600. K Items With the Maximum Sum

There is a bag that consists of items, each item has a number 1, 0, or -1 written on it. </br>

You are given four non-negative integers numOnes, numZeros, numNegOnes, and k. </br>

The bag initially contains: </br>

numOnes items with 1s written on them. </br>
numZeroes items with 0s written on them. </br>
numNegOnes items with -1s written on them. </br>
We want to pick exactly k items among the available items. </br>
Return the maximum possible sum of numbers written on the items. </br>

## Example 1:

Input: numOnes = 3, numZeros = 2, numNegOnes = 0, k = 2 </br>
Output: 2 </br>
Explanation: We have a bag of items with numbers written on them {1, 1, 1, 0, 0}. </br>
We take 2 items with 1 written on them and get a sum in a total of 2. </br>
It can be proven that 2 is the maximum possible sum. </br>

## Example 2:

Input: numOnes = 3, numZeros = 2, numNegOnes = 0, k = 4 </br>
Output: 3 </br>
Explanation: We have a bag of items with numbers written on them {1, 1, 1, 0, 0}. </br>
We take 3 items with 1 written on them, and 1 item with 0 written on it, </br>
and get a sum in a total of 3.</br>
It can be proven that 3 is the maximum possible sum. </br>

## Constraints:

0 <= numOnes, numZeros, numNegOnes <= 50 </br>
0 <= k <= numOnes + numZeros + numNegOnes </br>
