# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
try:
    file = open("story.txt", "r")
    count = 0
    for line in file:
        if not line.startswith('T'):
            count += 1
    print("Number of lines that do not start with 'T':", count)
    file.close()  
except FileNotFoundError:
    print("File not found")

## Output
<img width="213" height="99" alt="image" src="https://github.com/user-attachments/assets/270a1ea8-2c74-4afd-8f43-b027505986d2" />

## Result
Thus the python program is executed successfully.
