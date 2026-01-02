#Tags 

Problem

### Intuition
#### Approach
#### Code

```python
class Solution:
    def repeatedNTimes(self, nums: List[int]) -> int:
        seen = set()
        
        for num in nums:
            if num in seen:
                return num
            seen.add(num)
```
#### Complexity Analysis

- Time complexity: O(n)

- Space complexity: O(n)
