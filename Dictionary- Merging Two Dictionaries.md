
## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
a=eval(input())
b=eval(input())
c=a.copy()
c.update(b)
print(c)
```


## Output
![438927958-73844d5d-fea7-4dff-8ee5-c2483641e2c0](https://github.com/user-attachments/assets/f5d0d3cb-d3fe-4282-b01e-db598dfca37d)

## Result
Thus the program executed successfully.
