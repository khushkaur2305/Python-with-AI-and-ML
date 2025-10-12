# 📘 Day 05  

## ✅ Topic Covered
Deep Dive into **Python Dictionaries**, Dictionary Operations, and Practical Applications  

## 🧠 Summary
Today’s session focused on understanding **Python Dictionaries**, which are **unordered, mutable collections** of **key-value pairs**. We explored how to:

- Declare and initialize dictionaries  
- Access, modify, add, and remove key-value pairs  
- Perform operations like key existence check, iteration over keys, values, or items  
- Use built-in functions like `len()`, `keys()`, `values()`, `items()`, `get()`, and `pop()`  

Dictionaries are extremely useful for **storing related data** where each item has a unique identifier (key). Analogies helped in understanding: think of a dictionary as a **real-world dictionary** where a word (key) maps to its meaning (value).  

---

## 🧪 Examples & Concepts Practiced

| Concept/Feature     | Example                                  | Purpose/Use Case                             |
|-------------------|------------------------------------------|---------------------------------------------|
| Declare Dictionary  | `student = {"name": "Khush", "age": 20}` | Store key-value pairs                        |
| Access Value        | `student["name"]` → `"Khush"`           | Retrieve value by key                        |
| Modify Value        | `student["age"] = 21`                   | Update existing value                        |
| Add Key-Value       | `student["city"] = "Delhi"`             | Add a new key-value pair                      |
| Remove Key-Value    | `del student["age"]`                     | Delete a key-value pair                       |
| Get Method          | `student.get("name")`                    | Retrieve value safely                         |
| Keys & Values       | `student.keys()`, `student.values()`    | Access all keys or values                     |
| Iteration           | `for k, v in student.items(): print(k, v)` | Loop through dictionary                        |
| Length              | `len(student)`                           | Count number of key-value pairs               |
| Membership Check    | `"name" in student`                      | Check if key exists                            |

---

## 🔍 New Concepts Learned
- Dictionaries are **mutable** and **unordered**.  
- Keys must be **unique and immutable**, values can be any datatype.  
- Built-in functions provide quick ways to access keys, values, or key-value pairs.  
- Ideal for mapping relationships like **student → marks**, **product → price**, etc.  

---

## 💻 Activity
- Declared dictionaries with personal data and product info.  
- Accessed and modified values using keys.  
- Added and removed key-value pairs.  
- Practiced iterating over keys, values, and items.  
- Compared dictionaries with lists and tuples to understand use cases.  

---

## 🤔 Challenges Faced
Remembering the difference between accessing a value directly (`dict[key]`) vs safely using `get()` was tricky initially.  

---

## 🎯 Key Takeaway
Dictionaries are **efficient for mapping relationships**. They allow fast lookup, insertion, and deletion using unique keys.  

---

## 📈 Understanding Today: 9/10  

---

