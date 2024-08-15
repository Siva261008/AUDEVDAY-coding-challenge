Harry wants to sell lottery tickets and earn money out of it . In his basic research that most lottery tickets follow some logic in deciding the winning ticket number. He studies many algorithms for the same and finally decided in to device algorithm.

Every day he provides 2 numbers as an input to the algorithm which is N
, K
 where N
 is number of primes to be used in algorithm and K
 is a single digit odd number.

Algorithm WinningTicket Number(N
,K
):

Step 1 . Create a list L of first N prime number that end with digit K and include 2 and 5 in that list.

Step 2. Find the sum of all numbers of L
 and denote its sum as S
.

Step 3. Print the sum S as the winning ticket number for that day.

Input
The first line of input contains integers separated by space N
 and K
.

1<N<1000
K
 can take values 1,3,7,9
Output
A single line of output consisting of sum S which is the winning ticket number for that day.

Examples
Input
5 7
Output
182
Input
10 3
Output
677
Note
In first test case list will be 2,5,7,17,37,47,67
 which when added results in 182
.

In second test case list will be 2,5,3,13,23,43,53,73,83,103,113,163
 which when added results in 677
.
