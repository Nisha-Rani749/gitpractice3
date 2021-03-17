# THSCohortF2020-Anagha
## General info
Coding problems for lab hours.
## Coding Language:
Javascript.
## Problem Statements :
### Lab 1 :-
Print all Prime Numbers in a given array and Swap Numbers using temp variable, `+,- operator`, `*/ operator`, `XOR operator`, `XNOR operator`.
#### Test Case for Prime Number :
```
Input:
array = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,23,97];
Output:
primeArr = [2,3,5,7,11,13,23,97];
```
### Lab 2 :-
Extract Prime Numbers From Array
#### Test Cases :
```
Input:
array = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15];
Output:
primeArr = [2,3,5,7,11,13];
```
### Lab 3 :-
Given an array of positive integer  elements.Print out the count of Prime Numbers and Narcissistic numbers from the array and remove those elements from the array.
##### Test Cases :
```
Sample Input 1 :10,20,30,40,2,5,7,153,1024,1634,11
Expected Output format :
Prime Numbers Count : 4
Narcissistic Numbers Count : 5
The updated array : `10,20,30,40,1024`
```
### Lab 4 :-
Create an interactive command line program that continually takes a command line input from the user until the number is multiple of 11.
#### Test Cases :
```
Sample Input 1 :
Enter the number : 5
Expected Output format :5 is not multiple of 11. Try again.
```
### Lab 5 :-
Write an Algorithm to take an input String 'S' with length 'N', split the string into two strings based on even and odd indexes while left padding the sub string with '000' and right padding the substring with '111'.
#### Test Cases :
```
Sample Input 1 :
code.in
Sample Output 1 :
000cd.n111
000oei111
Sample Input 2 :
Hello there
Sample Output 2 :
000Hlotee111
000el hr111
```
### Lab 6 :-
Write an Algorithm to implement ROT13 ("rotate by  13 places", sometimes hyphenated ROT-13)
#### Description
About `ROT13`: Its a piece of text merely requires examining its alphabetic characters and
replacing each one by the letter 13 places further along in the alphabet, wrapping back to the
beginning if necessary.[2] A becomes N, B becomes O, and so on up to M, which becomes Z,
then the sequence continues at the beginning of the alphabet: N becomes A, O becomes B, and
so on to Z, which becomes M. Only those letters which occur in the English alphabet are
affected; numbers, symbols, whitespace, and all other characters are left unchanged. Because
there are 26 letters in the English alphabet and 26 = 2 × 13, the ROT13 function is its own
inverse:[2]
#### Test Cases :
```
Sample Input: apple
Sample Output: nccyr
Sample Input: Jack & Jill
Sample Output: Xnpx & Xvyy
```
### Lab 7 :- 
Write an algorithm to remove duplicate elements in a gen input array and print the total number of elements removed.
#### Test Cases :
```
Sample Input : [1, 2, 2, 3, 4, 4, 4, 5, 5]
Sample Output : [1, 2, 3, 4, 5]
Number of Elements Removed : 4
 ```
### Lab 8 :-
Write an algorithm to rotate the bits of a given input number.
#### Test Cases :
```
Sample Input: 16 //left
Sample Output: 10000
Left Rotated Bits: 01000000
Sample Input: 45 //right
Sample Output: 101101
Right Rotated Bits: 01001011
```
### Lab 9 :-
Defang IPv4 and Validate
#### Test Cases :
```
Sample Input:  255.64.12.11
Sample Output: 255.64.12.11
valid IP
Defanged IP: 255[.]64[.]12[.]11
Sample Input: 255.642.32.11
Sample Output: 255.642.32.11
Invalid IP
```
### Lab 10 :-
Write a CLI program to find sum of the diagonal elements, along with absolute difference and diagonal difference.
#### Test Cases :
```
Solution 1 : m x n 
Menu Options : 
               1) Diagonal Difference
               2) Sum of all the Diagonal Elements(Both d1 and d2)
               3) Diagonal Abs Difference
               0) Exit.
After User Input Matrix Elements
1 2 3
4 5 6
7 8 9
Input: 2 //sum
Output: 32 
```
### Lab 11 :- 
Check given matrix is Valid Magic square matrix or not.
#### Test Cases :
```
Input : n = 3
2n elements in Array
[2,5,1,3,4,7]
[x1,x2,x3,y1,y2,y3]
O/P : [2,3,5,4,1,7]
(x1,y1) = (2,3)
(x2,y2) = (5,4)
(x3,y3) = (1,7)
```
### Lab 12 :- 
Given a sorted array of distinct  integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.
#### Test Cases :
```
Sample Input 1 :
Array : [1,3,5,6]
Target Element : 5
o/p : 2
Sample Input 2 :
Array : [1,3,5,6]
Target Element : 7
o/p : 4
```
### Lab 13 :- 
Given a sorted array of distinct integers and a target value, return the index if the target is found. If not, return the index where it would be if it were inserted in order.
#### Test Cases :
```
Sample Input 1 :
Array : [1,3,5,6]
Target Element : 5
O/p : 2
Sample Input 2 :
Array : [1,3,5,6]
Target Element : 7
O/p : 4
```
### Lab 14 :- 
Given a non-negative integer num, return the number of steps to reduce it to zero. If the current number is even, you have to divide it by 2, otherwise, you have to subtract 1 from it.
#### Test Cases :
```
Sample Input 1 :
Input: num = 14
Output: 6 (No Of Steps) , Please Print the steps like below with values.
Sample Input 2 :
Input: num = 8
Output: 4 (No of Steps), Please Print the steps like below with values.
```
