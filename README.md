# Weird-Palindrome-Making-

## Weird Palindrome Making Problem Code: MAKEPAL Solved Submit
Read problem statements in Bengali and Russian.
Naveej is from a tribe that speaks some weird language - their alphabet consists of N
 distinct characters. He has an array A=[A1,A2,…,AN]
, where Ai
denotes the number of occurrences of the i
-th character with him.

He wants to make a palindromic string using all the characters he has (every character he has must be used in this string).

In order to make this possible, he can perform the following operation:

Select an i
 (1≤i≤N)
 and convert all occurrences of i
-th alphabet to any other alphabet of his choice.
Note that Naveej just wants to be able to make any palindrome, as long as every character is used. For example, if N=2
 and A=[2,2]
 and we consider the characters to be a
 and b
, he can make both abba
 and baab
, but aba
 is not allowed because it uses only 3
 characters.

Find the minimum number of operations required such that Naveej can make a palindromic string using all the characters he has. It can be proven that there always exists at least one sequence of operations allowing for the formation of a palindrome.

## Input Format
The first line of input contains a single integer T
 denoting the number of test cases. The description of T
 test cases follows.
The first line of each test case contains a single integer N
 - the size of the alphabet.
The second line contains N
 space-separated integers: A1,A2,...,AN
, where Ai
 is the number of occurrences of the i
-th character with Naveej.
## Output Format
For each test case, output a single line containing one integer - the minimum number of operations required so that Naveej can make a palindromic string using all the characters he has.

## Constraints
1≤T≤1000
1≤N≤2⋅105
1≤Ai≤109
It is guaranteed that the sum of N
 over all test cases does not exceed 2⋅105
Subtasks
Subtask 1 (100 points): Original constraints
## Sample Input 1 
2
1
4
3
4 3 1
## Sample Output 1 
0
1
