# CountTrue Function

## Overview

The `counttrue` function is a simple Python function designed to count the number of `True` values in a given list or array. This function iterates through the provided array and checks if each element is `True`. If so, it increments a counter and returns the final count.

## Function Definition

```python
def counttrue(array):
    count = 0
    for i in array:
        if i:
            count += 1
    return count
