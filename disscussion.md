# Disscussion
## A approach to implement a function:
1. Pick an example input and correponding output.
2. Describle a process in english that computes output from input in a simple step.
3. Figue out what addtional name you'll need to carry out.
4. Implement the process using these addtional name.
5. Determine whether these implementation work on original example.
6. Determine whether these implementation work on other example.

### importantly:
don't check your implementation using computer right away

## Is_prime 
1. check n is or not 1.if it is return False.
2. for i in range from 2 to n-1
3. check if n%i == 0
4. if is return false

## Unique digits
**Write a Function that return number of unique digits in a positive integer**
the one idea: draw out the last one of integer and check the rest one if have the same number
main function:
1. using n%10 draw out the last one(last)
2. using a function check the rest one
check function:
1. jieshou two arguement n and k(the last)
2. using n = n//10 xioachu the last one
3. set a while loop check k == the last one

the other one: check the integer with 0-9
main function:
1. using while loop through out 0-9
2. using check function
