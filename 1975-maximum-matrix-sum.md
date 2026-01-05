#medium #array #greedy #matrix #review 

You are given an `n x n` integer `matrix`. You can do the following operation **any** number of times:

- Choose any two **adjacent** elements of `matrix` and **multiply** each of them by `-1`.

Two elements are considered **adjacent** if and only if they share a **border**.

Your goal is to **maximize** the summation of the matrix's elements. Return _the **maximum** sum of the matrix's elements using the operation mentioned above._

**Example 1:**

![[Pasted image 20260105161255.png]]

**Input:** matrix =[[1,-1],[-1,1]]
**Output:** 4
**Explanation:** We can follow the following steps to reach sum equals 4:
- Multiply the 2 elements in the first row by -1.
- Multiply the 2 elements in the first column by -1.

**Example 2:**

![[Pasted image 20260105161701.png]]

**Input:** matrix = [[1,2,3],[-1,-2,-3],[1,2,3]]
**Output:** 16
**Explanation:** We can follow the following step to reach sum equals 16:
- Multiply the 2 last elements in the second row by -1.

**Constraints:**

- `n == matrix.length == matrix[i].length`
- `2 <= n <= 250`
- `-105 <= matrix[i][j] <= 105`

#### Approach

If there's an even count of negative numbers, we can eventually flip them all to positive values -> Maximum Sum (best case scenario)

But if the count is odd, we will always be stuck with at least one negative number. The idea is to make this number the smallest number in the matrix (in abs)

answer = (sum of absolute values) − (2 × smallest if odd negatives)
	
#### Code

```python
class Solution:
	def maxMatrixSum(self, matrix: List[List[int]]) -> int:
		total_sum = 0 
		min_abs_val = float("inf")
		negative_count = 0
	
		for row in matrix:
			for val in row:
				total_sum += abs(val)
				if val < 0:
					negative_count += 1
				min_abs_val = min(min_abs_val, abs(val))
	
		if negative_count % 2 != 0:
			total_sum -= 2 * min_abs_val
		return total_sum
```
#### Complexity Analysis

- Time complexity: O(n²)

- Space complexity: O(1)
