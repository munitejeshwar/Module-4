#EX 4a Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
dict1 = eval(input())
dict2 = eval(input())

dict1.update(dict2)
print(dict1)
```

## Output
<img width="1142" height="172" alt="Screenshot 2025-11-22 093341" src="https://github.com/user-attachments/assets/21fff779-9649-4908-8c81-573a2214ab78" />

## Result
Thus, the program successfully merges dictionary1 with dictionary2 and displays the combined dictionary.

## EX 4b: Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
age = int(input())
print("Age is:")
print(age)

try:
    if age < 0:
        raise ValueError("Input Correct age.")
    else:
        year_of_birth = 2022 - age
        print("Year of Birth is:")
        print(year_of_birth)
except ValueError as e:
    print(e)
```

## Output
<img width="584" height="283" alt="Screenshot 2025-11-22 093546" src="https://github.com/user-attachments/assets/7d35e4e1-e7ef-4127-bb1d-14a8951e1b4d" />


## Result
Thus, the program successfully checks if the age is negative and raises an exception using the raise keyword.

#EX 4c: Dictionary-Python Program to Sort a Dictionary by Keys and Values

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
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def read_file(file_path):
    with open(file_path, 'r') as file:
        return file.read()

def reverse_file_content(input_file_path, output_file_path):
    with open(input_file_path, 'r') as file:
        content = file.read()
    with open(output_file_path, 'w') as file:
        file.write(content[::-1])
```

## Sample Output
<img width="1136" height="335" alt="Screenshot 2025-11-22 093742" src="https://github.com/user-attachments/assets/1cabef6b-1274-4469-8040-38195112eab0" />


## Result
Thus, the Python program successfully reversed the contents of a file and saved the reversed text into another file.


# EX 4d: Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
class CSE:
    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def mul(self):
        print("Result: ", self.a * self.b)

    def div(self):
        if self.b != 0:
            print("Result: ", self.a // self.b)
        else:
            print("Cannot divide by zero")

a = int(input())
b = int(input())

obj = CSE()
obj.setvalues(a, b)
while True:
    choice = int(input())
    if choice == 1:
        obj.mul()
    elif choice == 2:
        obj.div()
    elif choice == 0:
        print("Exiting!")
        break
    else:
        print("Invalid choice")
```

## Output
<img width="443" height="288" alt="Screenshot 2025-11-22 093916" src="https://github.com/user-attachments/assets/c8c0b9f4-c315-4294-92bb-69dfc433da3d" />


## Result
Thus, the Python program using a class and conditional statements successfully performed multiplication or floor division based on the user's choice.


# EX 4e: File Handling in Python: Count Lines Not Starting with 'T'

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
```
n = int(input())
a, b = 0, 1

for i in range(n):
    print(a)
    a, b = b, a + b
```


## Output
<img width="415" height="417" alt="Screenshot 2025-11-22 094053" src="https://github.com/user-attachments/assets/166e68cc-b52b-46e6-af89-0634be3c94fe" />

## Result
Thus, the program successfully generated the Fibonacci series for the given number of terms.
