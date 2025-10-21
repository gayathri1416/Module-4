## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

d1=eval(input())
d2=eval(input())
def merge(dict1,dict2):
     res={**dict1,**dict2}
     return res
print(merge(d1,d2))

## Output
<img width="1041" height="172" alt="image" src="https://github.com/user-attachments/assets/0efa6f6d-5e32-4b7e-80a0-e9dffb83e77e" />

## Result
Thus the python program to merge the two dictionary is executed successfully.
