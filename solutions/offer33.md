参考255题
- time: O(n)
- space: O(n)


```python
class Solution:
    def verifyPostorder(self, postorder: List[int]) -> bool:
        root = float("inf")
        stack = []
        for i in range(len(postorder)-1, -1, -1):
            if postorder[i] > root: return False
            while stack and stack[-1] > postorder[i]:
                root = stack.pop()
            stack.append(postorder[i])
        return True
```