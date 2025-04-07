# CMPS 2200 Recitation 06
## Answers

**Name:** Jaret Solomon


Place all written answers from recitation-06.md here for easier grading.

2) W(n) = W(n-1) + W(n-2) + O(1)

Base Case: n=1: W(n)=O(2^n-1)+O(2^n-2)+O(1)=O(2^n) || 
    (O(2^n) largest complexity overrides)


3) S(n-1)+O(1)=O(n)

4) The counts list repeats the sequence and overwrites the values that were already calculated leading to the final sequence.

6) It will be called the maximum n times due to the iteration going through every value. This makes both the work and span = O(n).

8) It will be read n-2 times at a maximum. This leads to the complexity of both work and span of fib_bottom_up is O(n).
