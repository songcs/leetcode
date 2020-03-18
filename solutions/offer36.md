# 中序遍历

```python
"""
# Definition for a Node.
class Node:
    def __init__(self, val, left=None, right=None):
        self.val = val
        self.left = left
        self.right = right
"""
class Solution:
    def treeToDoublyList(self, root: 'Node') -> 'Node':
        if not root:
            return None
        
        def construct(node, prev):
            if not node:
                return prev
            prev = construct(node.left, prev)
            prev.right = node
            node.left = prev
            prev = node
            cur_tail = construct(node.right, prev)
            return cur_tail
        
        dummy = Node(0)
        tail = construct(root, dummy)
        head = dummy.right
        head.left = tail
        tail.right = head
        return head
```
