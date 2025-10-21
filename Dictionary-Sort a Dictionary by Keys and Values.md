# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
from collections import OrderedDict
dict_data = {'ravi':'10','rajnish':'9','sanjeev':'15','yash':'2','suraj':'32'}
sorted_dict = OrderedDict(sorted(dict_data.items()))
print(sorted_dict)

## Sample Output
<img width="1618" height="196" alt="image" src="https://github.com/user-attachments/assets/51509d7f-9434-4eb9-9f4d-96ba06660a42" />

## Result
Thus the python program is executed successfully.
