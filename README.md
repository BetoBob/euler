# euler

Partial Solutions are those that can pass at least one test case.

| Problem                                                      | Description            | Partial Solution | Complete Solution | Notes                                                        |
| ------------------------------------------------------------ | ---------------------- | ---------------- | ----------------- | ------------------------------------------------------------ |
| 001                                                          |                        | Y                |                   |                                                              |
| [002](https://www.hackerrank.com/contests/projecteuler/challenges/euler002/problem?h_r=profile) | Fibonnaci sum of evens | Y                | Y                 | can solve more efficiently by skipping some odd calculations??? |
| [253](https://www.hackerrank.com/contests/projecteuler/challenges/euler253/problem) |                        |                  |                   |                                                              |
| 254                                                          |                        | Y                |                   |                                                              |



The average in this case is the sum of (M * m_possibilities) divided by the sum of possible outcomes. For the case of `n = 10`, it would look something like this:

```python
# average for n = 10

((1 * 512) + (2 * 250912) + (3 * 1815264) + (4 * 1418112) + (5 * 144000)) / (512 + 250912 + 1815264 + 1418112 + 144000)
```

```
3.400731922398589
```

What does this number mean? When you are building a caterpillar of length `n = 10`, you are on average most likely to have a maximum of 3 - 4 segments.