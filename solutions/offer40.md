# 快排

- 80ms
- 72%

```python
class Solution:
    def getLeastNumbers(self, arr: List[int], k: int) -> List[int]:
        

        def quickSort(l, r):
            if l>r: return
            pos = partition(l, r)
            if pos + 1 == k:
                return
            elif pos + 1 > k:
                quickSort(l, pos-1)
            else:
                quickSort(pos+1, r)

        def partition(l, r):
            pivot = arr[r]
            i = l
            for j in range(l, r):
                if arr[j] < pivot:
                    arr[i], arr[j] = arr[j], arr[i]
                    i += 1
            arr[i], arr[r] = arr[r], arr[i]
            return i
        
        quickSort(0, len(arr)-1)
        return arr[:k]
```


- 652ms
- 6%


```python
class Solution:
    def getLeastNumbers(self, arr: List[int], k: int) -> List[int]:
        small = []
        equal = [arr[0]]
        big = []
        for n in arr[1:]:
            if n > arr[0]:
                big.append(n)
            elif n < arr[0]:
                small.append(n)
            else:
                equal.append(n)
        if len(small) > k:return self.getLeastNumbers(small, k)
        if len(small) + len(equal) >= k: return small + equal[:k-len(small)]
        return small + equal + self.getLeastNumbers(big, k-len(small)-len(equal))
```