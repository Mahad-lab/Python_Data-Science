## Numpy
* * *

### Import numpy
`import numpy as np`

### Creating an array
```python
arr = np.array([1,2,3,4])`

print(arr)
>>> [1 2 3 4]
```

### Finding length of array
`arr.size`

```python
print(arr.size)
>>> 4
```

### Finding dimensions of array
`arr.shape`

```python
print(arr.shape)
>>> (4,0)
```

### Changing dimention of array
`arr.reshape((2,2))`

```python
arr = arr.reshape((2,2))

print(arr)
>>> array([[1, 2],
		   [3, 4]])
```

### Getting array data type
`arr.dtype`

```python
print(arr.dtype)
>>> int64
```

and

```python
arr2 = np.array([1,2.0,3,4])
print(arr2)
>>> [1. 2. 3. 4.]
print(arr2.dtype)
>>> float64
```

### Selecting element for array
`arr[0]`

```python
print(arr[0])
>>> 1
```
