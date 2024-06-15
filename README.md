## 2024-06-15
### Find the longest word in a sentence
```Python
longest_word = max(sentence.split(), key=len)
```

Example:
```Python
longest_word = max('This is a test sentence'.split(), key=len)
```


## 2024-06-12
### Find the longest word in a sentence
```Python
longest_word = max(sentence.split(), key=len)
```

Example:
```Python
longest_word = max('This is a test sentence'.split(), key=len)
```


## 2024-06-12
### Iterate over a list with an index
```Python
for index, value in enumerate(list):
```

Example:
```Python
for index, value in enumerate(['a', 'b']):
```


## 2024-06-12
### Sort a dictionary by value
```Python
sorted_dict = {k: v for k, v in sorted(dict.items(), key=lambda item: item[1])}
```

Example:
```Python
sorted_dict = {k: v for k, v in sorted({'a': 3, 'b': 1}.items(), key=lambda item: item[1])}
```


## 2024-06-11
### Use a dictionary to switch cases
```Python
def switch(case): return {'a': 1, 'b': 2}.get(case, 0)
```

Example:
```Python
switch('a')
```


## 2024-06-11
### Find the intersection of two lists
```Python
intersection = list(set(list1) & set(list2))
```

Example:
```Python
intersection = list(set([1, 2, 3]) & set([2, 3, 4]))
```


## 2024-06-10
### Convert a list of tuples into separate lists
```Python
list1, list2 = zip(*list_of_tuples)
```

Example:
```Python
list1, list2 = zip(*[(1, 'a'), (2, 'b')])
```


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


