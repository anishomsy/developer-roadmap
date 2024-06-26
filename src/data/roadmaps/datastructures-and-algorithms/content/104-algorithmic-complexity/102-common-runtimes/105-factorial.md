# Factorial

Factorial, often denoted as `n!`, is a mathematical operation. In the context of computer science and algorithm complexity, it represents an extremely high growth rate. This occurs because of the way a factorial is calculated: The product of all positive integers less than or equal to a non-negative integer `n`. Thus, if an algorithm has a complexity of O(n!), it means the running time increases factorially based on the size of the input data set. That is, for an input of size `n`, the algorithm does `n` * `(n-1)` * `(n-2)` * ... * `1` operations. O(n!) is essentially the worst case scenario of complexity for an algorithm and is seen in brute-force search algorithms, such as the traveling salesman problem via brute-force.

Example:
```python
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n-1)
```
