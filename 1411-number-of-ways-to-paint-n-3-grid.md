#hard #dynamic-programming #review

You have a `grid` of size `n x 3` and you want to paint each cell of the grid with exactly one of the three colors: **Red**, **Yellow,** or **Green** while making sure that no two adjacent cells have the same color (i.e., no two cells that share vertical or horizontal sides have the same color).

Given `n` the number of rows of the grid, return _the number of ways_ you can paint this `grid`. As the answer may grow large, the answer **must be** computed modulo `109 + 7`.

**Example 1:**

<img src="imgs/Pasted image 20260103123525.png" width="300">

**Input:** n = 1
**Output:** 12
**Explanation:** There are 12 possible way to paint the grid as shown.

**Example 2:**

**Input:** n = 5000
**Output:** 30228214

**Constraints:**

- `n == grid.length`
- `1 <= n <= 5000`
#### Approach

Dynamic programming. TODO.
#### Code

```python
class Solution: 
	def numOfWays(self, n: int) -> int: 
		MOD = 10**9 + 7 
		
		type_abc = 6 
		type_aba = 6
		
		for _ in range(2, n + 1): 
			new_abc = (2 * type_abc + 2 * type_aba) % MOD 
			new_aba = (2 * type_abc + 3 * type_aba) % MOD 
			
			type_abc = new_abc 
			type_aba = new_aba 
			
		return (type_abc + type_aba) % MOD
	
```
#### Complexity Analysis

- Time complexity: O(n)

- Space complexity: O(1)
