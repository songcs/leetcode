# 解法一
- 432ms
- 23%


```python
class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        mask = [0] * 32
        idx = list(range(31, -1, -1))
        for n in nums:
            for i in idx:
                if (1<<i) & n:
                    mask[i] += 1
        ans = 0
        for i in idx:
            if mask[i] % 3 ==1:
                ans |= 1<<i
        return ans
```

# 解法二
- 60ms

## XOR

该运算符用于检测出现奇数次的位：1、3、5 等。

0 与任何数 XOR 结果为该数。

0 ^ x = x

两个相同的数 XOR 结果为 0。

x ^ x=0

以此类推，只有某个位置的数字出现奇数次时，该位的掩码才不为 0。
![pic](https://pic.leetcode-cn.com/Figures/137/xor.png)



因此，可以检测出出现一次的位和出现三次的位，但是要注意区分这两种情况。

## AND 和 NOT

为了区分出现一次的数字和出现三次的数字，使用两个位掩码：seen_once 和 seen_twice。

思路是：

仅当 seen_twice 未变时，改变 seen_once。

仅当 seen_once 未变时，改变seen_twice。

![pic](https://pic.leetcode-cn.com/Figures/137/three.png)
位掩码 seen_once 仅保留出现一次的数字，不保留出现三次的数字。

```python
class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        once, twice = 0,0
        for n in nums:
            once = ~twice & (once^n)
            twice = ~once & (twice^n)
        return once
```