--
marp: true
theme: custom
paginate: true
_paginate: true
class: lead
---

# Marp Presentation

📧 23f2001992@ds.study.iitm.ac.in

---

<!-- _class: lead -->
<!-- _backgroundImage: url('https://picsum.photos/1600/900') -->
# Slide with Background Image

This slide uses a random background image.

---

# Algorithmic Complexity

Here’s an example of mathematical equations:

$$
T(n) = O(n \log n)
$$

$$
\text{NPV} = \sum_{t=0}^{T} \frac{CF_t}{(1 + r)^t}
$$

---

# Code Example

```python
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
