# 📘 Day 02  

## ✅ Topic Covered
Deep Dive into **Python Datatypes**, Type Casting, and Runtime Data Handling  

## 🧠 Summary
Today’s session focused on understanding **Python datatypes**, their uses, and how they are fundamental to programming. We explored the four primary datatypes:

- **Integers (`int`)** – whole numbers  
- **Floats (`float`)** – decimal numbers  
- **Strings (`str`)** – text data  
- **Booleans (`bool`)** – True/False values  

We also learned about **type casting**, which allows converting data from one type to another, and practiced using the **`type()`** function to inspect variables at runtime.  
The session included using the **`input()`** function to take user data and dynamically convert it to the desired datatype for calculations and logic handling.  

Analogies made understanding easier: think of **integers** as solid blocks, **floats** as fluid numbers with fractions, **strings** as words written on paper, and **booleans** as simple yes/no switches.  

---

## 🧪 Examples & Concepts Practiced

| Concept/Feature     | Example                                  | Purpose/Use Case                             |
|-------------------|------------------------------------------|---------------------------------------------|
| Integer (`int`)     | `age = 20`                               | Counting, indexing, calculations           |
| Float (`float`)     | `height = 5.7`                           | Precision calculations, measurements       |
| String (`str`)      | `name = "Khushpreet"`                    | Storing text, messages, user input         |
| Boolean (`bool`)    | `is_student = True`                      | Conditional logic, decision making         |
| Type Casting        | `num_int = int("15")`                    | Convert between types for correct operations|
| Input Handling      | `user_age = int(input("Enter age: "))`   | Dynamic runtime data entry                  |
| Type Checking       | `type(name)`                              | Inspect variable datatype                   |

---

## 🔍 New Concepts Learned
- Everything in Python is an **object**, even numbers and booleans.  
- **Type casting** is essential to avoid runtime errors.  
- **`input()`** always returns a string by default; conversion is needed for numeric operations.  
- **`type()`** is useful to confirm variable datatype.  
- Understanding datatypes is crucial for **data validation** and **program efficiency**.  

---

## 💻 Activity
- Declared and printed variables of different datatypes.  
- Converted between types using `int()`, `float()`, and `str()`.  
- Took user input and dynamically used it in calculations.  
- Practiced checking variable types with `type()`.  

---

## 🤔 Challenges Faced
Initially, remembering which operations work with which datatype caused some confusion (e.g., concatenating numbers with strings requires conversion). Practicing type casting solved this issue.  

---

## 🎯 Key Takeaway
Datatypes are the building blocks of Python programs. Choosing the correct type ensures smooth calculations, accurate logic, and effective data handling.  

---

## 📈 Understanding Today: 9/10  

---

### Example Code Practiced
```python
# Python Datatypes Example

# Integer
age = 20
print(age, type(age))

# Float
height = 5.7
print(height, type(height))

# String
name = "Khushpreet"
print(name, type(name))

# Boolean
is_student = True
print(is_student, type(is_student))

# Type Casting
num_str = "15"
num_int = int(num_str)
print(num_int, type(num_int))

float_to_int = int(3.99)
print(float_to_int, type(float_to_int))

int_to_float = float(10)
print(int_to_float, type(int_to_float))

int_to_str = str(25)
print(int_to_str, type(int_to_str))

# Input Example
user_name = input("Enter your name: ")
print("Hello", user_name, type(user_name))

user_age = int(input("Enter your age: "))
print("Your age next year:", user_age + 1)

