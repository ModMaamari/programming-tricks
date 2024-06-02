## 2024-06-02
### Flatten a list of lists
```Python
flat_list = [item for sublist in list_of_lists for item in sublist]
```

Example:
```Python
flat_list = [item for sublist in [[1, 2], [3, 4]] for item in sublist]
```


