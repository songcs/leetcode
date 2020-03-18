```python
class Solution:
    def exchange(self, nums: List[int]) -> List[int]:
        l,r = 0, len(nums)-1
        while l < r:
            while l < r and nums[l]&1:
                l += 1
            while l < r and nums[r]&1==0:
                r -= 1
            if l<r:
                nums[l], nums[r] = nums[r], nums[l]
        return nums
```