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
```

data = {'b': 'banana', 'a': 'apple', 'd': 'date', 'c': 'cherry'}

print("Original Dictionary:", data)

sorted_keys = dict(sorted(data.items()))
print("Sorted by Keys:", sorted_keys)

sorted_values = dict(sorted(data.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_values)
```

## Sample Output


<img width="905" height="254" alt="image" src="https://github.com/user-attachments/assets/bdf2516c-75be-4c91-9253-451ef7987f0d" />

## Result

Thus, the Python program successfully sorts a dictionary alphabetically by keys and by values.
