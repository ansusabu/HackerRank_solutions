# HackerRank_solutions
## 1.Almost Sorted
[Problem](https://www.hackerrank.com/challenges/almost-sorted/problem)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/Almost%20Sorted)

**Logic**: Find the first elements which in not in sorted order from front and back. Swap bo the elements and see if the array is sorted or not. If not, reverse the array from the last non sorted element to the first non sorted element and see if the array is sorted or not

## 2.Caesar Cipher
[Problem](https://www.hackerrank.com/challenges/caesar-cipher-1/problem)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/Caesar%20Cipher)

**Logic**: A normal rotation is done. After z, it should start from a hence use %26


## 3.Common Child
[Problem](https://www.hackerrank.com/challenges/common-child/problem)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/Common%20Child)

**Logic**: This problem is solved using longest common subsequence algorithm

## 4.Separate the Numbers

[Problem](https://www.hackerrank.com/challenges/separate-the-numbers/problem)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/Separate%20the%20Numbers)

**Logic**: Take the first char and add one to it and check if the next number is same as expected. If the next number is same as expected, do the same and look if the numbers are same as our expected value. If the next number is not the one we expected, then take 2 values together and check. Do until half the string

## 5.Tower Breakers

[Problem](https://www.hackerrank.com/challenges/tower-breakers-1/problem)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/Tower%20Breakers)

**Logic**:If the height of the tower is 1, then 1st player won't be able to do any changes hence 2 wins. If the no of towers are odd, player 2 will do the same moves as player 1 until the last tower, where player 1 will be able to move but not player 2. If the no of towers are even, the payer 2 do the same moves as of player 1 and player 2 wins as he is the one who will be moving the last tower


## 10. 3D Surface Area
[Problem](https://www.hackerrank.com/challenges/3d-surface-area/problem?isFullScreen=true)

[Solution](https://github.com/ansusabu/HackerRank_solutions/blob/main/Solution/3D%20Surface%20Area)

**Logic**: I have taken 3 conditions for taking the surface area. 
1. No cubes on all the four sides, only stacking up,ie, on z-axis
2. 1 cube on the side of the corner piece, ie, the cubes are either stacked in x-axis and z-axis or y-axis and z-axis.
3. Cubes are stacked in both x-axis, y-axis and z-axis.

For all these cases, the surface area of each cube is calculated based on the corner peice, edge pice center piece etc and sums it up.


   
