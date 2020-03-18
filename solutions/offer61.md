```python
class Solution:
    def isStraight(self, nums: List[int]) -> bool:
        gap = 0
        nums.sort()
        for i in range(len(nums)-1):
            if nums[i] == 0:
                continue
            if nums[i] == nums[i+1]:
                return False
            gap += nums[i+1] - nums[i]
        return gap < 5
```