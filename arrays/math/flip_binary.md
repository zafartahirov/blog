# Flip Binary

Given a binary string $$S = S_0S_1\ldots S_{n-1}$$, where every character consists of either 0 or 1 ($$S_i = \{0,1\}$$). You are allowed to choose indexes $$0 \le \{L, R\} < n$$ and flip the substring $$S_{sub} = S_L\ldots S_R$$ to maximize the number of 1's in the resulting string. If the number of 1's is already maximum, return an empty array. If there are multiple possible solutions, return the lexicographically smaller.


## Example 1

```
Input: "010"
Output: [1, 1]
```

### Explanation
$$S = 010$$

Let's see what would be the result once we flip the bits for different values of $$L$$ and $$R$$.

| $$[L,R]$$ | $$S_{Result}$$ |
| :-------: | :------------: |
| [0, 0]    | 110            |
| [0, 1]    | 100            |
| [0, 2]    | 101            |
| [1, 1]    | 000            |
| [1, 2]    | 001            |

We see that for $$[L,R]$$ being [0, 0] and [0, 2], the number of 1's in the resulting string is 2. Because [0, 0] is lexicographically smaller, that's the answer.

## Example 2

```
Input: "111"
Ouput: []
```

### Explanation

There is no possible combination of $$L$$ and $$R$$ to increase the number of 1's in the input string.


<button class="section" target="solution" show="Show solution" hide="Hide solution"></button>

<!--sec data-title="Solution" data-id="solution" data-show=false ces-->

**Solution coming up... :)**

<!--endsec-->