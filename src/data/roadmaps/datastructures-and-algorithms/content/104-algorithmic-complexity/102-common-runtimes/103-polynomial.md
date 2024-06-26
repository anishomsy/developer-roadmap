# Polynomial

Polynomial time complexity, denoted as O(n^k), is a class of time complexity that represents the amount of time an algorithm takes to run as being proportional to the size of the input data raised to a constant power 'k'. Polynomial time complexity includes runtimes like O(n), O(n^2), O(n^3), etc. The value 'n' is a representation of the size of the input, while 'k' represents a constant. Algorithms running in polynomial time are considered to be reasonably efficient for small and medium-sized inputs, but can become impractical for large input sizes due to the rapid growth rate of function.

For example, the runtime of the following algorithm is n^2:
```python
def polynomial_algorithm(n):
    for i in range(n):
        for j in range(n):
            print(i, j)
```

Visit the following resources to learn more:

- [Big O Notation — Calculating Time Complexity](https://www.youtube.com/watch?v=Z0bH0cMY0E8)
- [Big O Notations](https://www.youtube.com/watch?v=V6mKVRU1evU)
