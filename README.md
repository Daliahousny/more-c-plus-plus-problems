# more-c-plus-plus-problems

Please write a mst Prim’s algorithm to solve the following problem with the same input and
print the output graph including nodes and vertices.

Question (2):
The ackermann function is one of those very difficult functions to compute and it’s a prime
example of non-primitive recursive functions, meaning it can’t be de-recursed and
rewritten into a loop (Check this video for a fun watch). The naive recursive
implementation suffers problems starting with ack(4, 1) and at the time of writing on a
machine with a 4.2GHz base CPU clock speed and 3200GHz 32GBs of DDR3 RAM is not
computable without further optimizations or settings applied.
The ackermann function is described using the equation below.
You are required to
1. Describe why the base Ackermann function is so heavy to compute
2. Write an optimization to make it’s calculation more efficient and possible for
arguments starting Ack(4, 1) and above
Inputs: 2 integers m & n where m & n >= 0
Output: ack(m, n)
Sample Inputs:
3 3
4 1
Sample Outputs:
61
65533
Note: In the case you’re not able to optimize it please also submit a file with the naive
implementation describing at the very least the first step of the solution where you
describe the problem with the Ackermann function itself.
