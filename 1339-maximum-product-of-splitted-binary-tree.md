#medium #tree #dfs #binary-tree
 
Given the `root` of a binary tree, split the binary tree into two subtrees by removing one edge such that the product of the sums of the subtrees is maximized.

Return _the maximum product of the sums of the two subtrees_. Since the answer may be too large, return it **modulo** `109 + 7`.

**Note** that you need to maximize the answer before taking the mod and not after taking it.

**Example 1:**

![](https://assets.leetcode.com/uploads/2020/01/21/sample_1_1699.png)

**Input:** root = [1,2,3,4,5,6]
**Output:** 110
**Explanation:** Remove the red edge and get 2 binary trees with sum 11 and 10. Their product is 110 (11*10)

**Example 2:**

![](https://assets.leetcode.com/uploads/2020/01/21/sample_2_1699.png)

**Input:** root = [1,null,2,3,4,null,null,5,6]
**Output:** 90
**Explanation:** Remove the red edge and get 2 binary trees with sum 15 and 6.Their product is 90 (15*6)

**Constraints:**

- The number of nodes in the tree is in the range `[2, 5 * 104]`.
- `1 <= Node.val <= 104`
#### Approach

DFS to find all subtree sums. For each subtree sum S, the other part has sum (total - S), so the product is S * (total - S). Find the max product across all possible splits.
#### Code

```python
class Solution:
    def maxProduct(self, root: Optional[TreeNode]) -> int:
        MOD = 10**9 + 7
        subtree_sums = []

        # dfs to find all subtree sums
        def dfs(node):
            if not node:
                return 0
            curr_sum = node.val + dfs(node.left) + dfs(node.right)
            subtree_sums.append(curr_sum)
            return curr_sum

        total_sum = dfs(root)

        max_product = 0
        for sum in subtree_sums:
            max_product = max(max_product, (total_sum - sum) * sum)

        return max_product % MOD
```
#### Complexity Analysis

- Time complexity: O(n)

- Space complexity: O(n)
