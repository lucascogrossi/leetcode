#medium #tree #bfs #binary-tree #review

Given the `root` of a binary tree, return _the level order traversal of its nodes' values_. (i.e., from left to right, level by level).

**Example 1:**

![](https://assets.leetcode.com/uploads/2021/02/19/tree1.jpg)

**Input:** root = [3,9,20,null,null,15,7]
**Output:** [[3],[9,20],[15,7]]

**Example 2:**

**Input:** root = [1]
**Output:** [[1]]

**Example 3:**

**Input:** root = []
**Output:** []

#### Approach

BFS + level-size tracking

Save len(q) before processing so you know where one level ends and the next begins
#### Code

```python
class Solution:
    def levelOrder(self, root: Optional[TreeNode]) -> List[List[int]]:
        q = deque()
        levels = []

        if root is None:
            return levels

        q.append(root)
        while q:
            qLen = len(q)
            level = []

            for i in range(qLen):
                node = q.popleft()
                level.append(node.val)

                if node.left is not None:
                    q.append(node.left)
                if node.right is not None:
                    q.append(node.right)

            levels.append(level)

        return levels
```
#### Complexity Analysis

- Time complexity: O(n)

- Space complexity: O(n)
