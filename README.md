## 2024-07-06
### Print a list of objects in tabular format
```Python
from tabulate import tabulate; print(tabulate(list_of_dicts, headers='keys'))
```

Example:
```Python
from tabulate import tabulate; print(tabulate([{'a': 1, 'b': 2}, {'a': 3, 'b': 4}], headers='keys'))
```


## 2024-07-04
### Find the mode of a list
```Python
mode = max(set(list), key=list.count)
```

Example:
```Python
mode = max(set([1, 2, 2, 3, 3, 3]), key=[1, 2, 2, 3, 3, 3].count)
```


## 2024-06-28
### Find the mode of a list
```Python
mode = max(set(list), key=list.count)
```

Example:
```Python
mode = max(set([1, 2, 2, 3, 3, 3]), key=[1, 2, 2, 3, 3, 3].count)
```


## 2024-06-28
### Group elements of a list based on a condition
```Python
from itertools import groupby; grouped = {k: list(v) for k, v in groupby(sorted(list, key=condition), key=condition)}
```

Example:
```Python
from itertools import groupby; grouped = {k: list(v) for k, v in groupby(sorted(['a', 'aa', 'b', 'bb'], key=len), key=len)}
```


## 2024-06-27
### Find the n largest elements in a list
```Python
import heapq; n_largest = heapq.nlargest(n, list)
```

Example:
```Python
import heapq; n_largest = heapq.nlargest(3, [1, 3, 2, 5, 4])
```


## 2024-06-26
### Count the frequency of elements in a list
```Python
from collections import Counter; freq = Counter(list)
```

Example:
```Python
from collections import Counter; freq = Counter([1, 2, 2, 3, 3, 3])
```


## 2024-06-25
### Measure the execution time of a code block
```Python
import time; start = time.time(); # your code here; end = time.time(); print(end - start)
```

Example:
```Python
import time; start = time.time(); sum(range(100000)); end = time.time(); print(end - start)
```


## 2024-06-24
### Measure the execution time of a code block
```Python
import time; start = time.time(); # your code here; end = time.time(); print(end - start)
```

Example:
```Python
import time; start = time.time(); sum(range(100000)); end = time.time(); print(end - start)
```


## 2024-06-24
### Generate Fibonacci sequence
```Python
fib = lambda n: n if n <= 1 else fib(n-1) + fib(n-2)
```

Example:
```Python
fib(10)
```


## 2024-06-23
### Check if a number is prime
```Python
is_prime = lambda x: all(x % i != 0 for i in range(2, int(x**0.5) + 1))
```

Example:
```Python
is_prime(29)
```


## 2024-06-21
### Find the greatest common divisor of two numbers
```Python
import math; gcd = math.gcd(a, b)
```

Example:
```Python
gcd = math.gcd(8, 12)
```


## 2024-06-20
### Calculate the factorial of a number using recursion
```Python
def factorial(n): return 1 if n == 0 else n * factorial(n - 1)
```

Example:
```Python
factorial(5)
```


## 2024-06-19
### Calculate the factorial of a number using recursion
```Python
def factorial(n): return 1 if n == 0 else n * factorial(n - 1)
```

Example:
```Python
factorial(5)
```


## 2024-06-18
### Check if a string contains a substring
```Python
contains = substring in string
```

Example:
```Python
contains = 'test' in 'This is a test'
```


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


