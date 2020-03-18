令s[x]为x的数位和
当 (x+1) % 10 ==0时： s[x+1] = s[x]-8 例如 19, 20 的数位和分别为 10, 2；
当 (x+1) % 10 !=0时： s[x+1] = s[x]+1, 例如 1, 21,2 的数位和分别为 1, 21,2 。

- time: O(mn)
- space: O(mn)

```python
class Solution:
    def movingCount(self, m: int, n: int, k: int) -> int:
        queue = [(0,0,0,0)]
        visited = set()
        while queue:
            tmp = []
            for r, c, sr, sc in queue:
                if r<0 or r>=m or c<0 or c>=n or k<(sr+sc) or (r,c) in visited: continue
                visited.add((r,c))
                tmp.append((r+1, c, sr+1 if (r+1)%10!=0 else sr-8, sc))
                tmp.append((r, c+1, sr, sc+1 if (c+1)%10!=0 else sc-8))
            queue = tmp
        return len(visited)
```