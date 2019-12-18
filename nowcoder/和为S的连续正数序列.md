# python
```python
# -*- coding:utf-8 -*-
class Solution:
    def FindContinuousSequence(self, tsum):
        # write code here
        l, r, s = 1,2,3
        ans = []
        while l<=tsum/2:
            if s < tsum:
                r += 1
                s += r 
            elif s > tsum:
                s -= l 
                l += 1
            else:
                temp = list(range(l, r+1))
                ans.append(temp)
                s -= l
                l += 1
        return ans
```