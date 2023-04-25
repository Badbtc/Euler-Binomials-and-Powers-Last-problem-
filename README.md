<a>The solution to Euler's Binomials and Powers problem is as follows:</a>

We need to find the number of nCr values that are greater than one-million for 1 ≤ n ≤ 100. Here are the steps to solve this problem:

1-Create a function that calculates the value of nCr using the formula n!/(r!*(n-r)!).

2-Iterate through all values of n from 1 to 100, and for each value of n, iterate through all values of r from 0 to n.

3-Calculate the value of nCr using the function created in step 1.

4-If the value of nCr is greater than one million, increment a counter variable.

5-After iterating through all values of n and r, the value of the counter variable will be the solution to the problem.
