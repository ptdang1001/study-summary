# 20200526@numpy.append
```python
import numpy as np
test=np.array([])
np.append(test,[3])
```
******************

# 20200527@arrayAsParametersOfFunction
```python
#using array.copy() if using array as parameters of function especially when you need to change the elements inside array
def test(arr):
    #change arr

test(arr.copy())
```
