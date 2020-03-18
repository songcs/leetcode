# 模拟
- time: O(n)
- space: O(n)
- 36ms
- 97%

```python
class Solution:
    def validateStackSequences(self, pushed: List[int], popped: List[int]) -> bool:
        j = 0
        st = []
        n = len(pushed)
        for i in range(n):
            st.append(pushed[i])
            while st and j < n and st[-1] == popped[j]:
                st.pop()
                j += 1
        return not st
```