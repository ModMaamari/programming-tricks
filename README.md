## 2024-06-09
### Remove duplicates from a list while preserving order
```Python
seen = set(); no_duplicates = [x for x in list if not (x in seen or seen.add(x))]
```

Example:
```Python
seen = set(); no_duplicates = [x for x in [1, 2, 2, 3, 1] if not (x in seen or seen.add(x))]
```


## 2024-06-06
### Transpose a matrix
```Python
transposed = list(zip(*matrix))
```

Example:
```Python
transposed = list(zip(*[[1, 2], [3, 4]]))
```


## 2024-06-05
### Reverse a list
```Python
reversed_list = list[::-1]
```

Example:
```Python
reversed_list = [1, 2, 3][::-1]
```


## 2024-06-03
### Check if all elements in a list are unique
```Python
unique = len(list) == len(set(list))
```

Example:
```Python
unique = len([1, 2, 3, 3]) == len(set([1, 2, 3, 3]))
```


## 2024-06-02
### Convert a list of strings to a single string
```Python
single_string = ''.join(list_of_strings)
```

Example:
```Python
single_string = ''.join(['a', 'b', 'c'])
```


