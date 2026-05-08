# 📝 Worksheet: 02 - Working with Data

Use this worksheet to review and reinforce your understanding of Python data containers.

---

## 🧠 Section 1: Lists

1. What method adds an item to the end of a list?  
   `Answer:`  .append(item)

2. How can you remove an item from a list by value?  
   `Answer:`  .remove(item) or .pop(index)

3. What’s the result of this code?

```python
nums = [2, 4, 6]
nums.append(8)
print(nums)
```

   `Answer:` 2, 4, 6, 8

---

### ✏️ Task: List Practice

```python
# Create a list of your top 3 favorite foods.
# Add another food to the list.
# Remove one item and print the list.

my_list = ['Pizza', 'Tacos', 'Ramen']
my_list.append("Burgers")
my_list.pop(0)
print(my_list)
```

---

## 🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?  
   `Answer:` List are mutable and Tuples are immutable

5. Can you change the contents of a tuple once it is created? Why or why not?  
   `Answer:` No, you can't because tuples are immutable

---

### ✏️ Task: Tuple Practice

```python
# Create a tuple with your favorite 3 numbers.
# Unpack it into three variables and print each.
camila_Birthday(8, 8, 6)
8, 8, 6 = camila_Birthday
print(camila_Birthday)


```

---

## 🔑 Section 3: Dictionaries

6. What does the `.get()` method do differently from accessing a key directly?  
   `Answer:` Returns the value if the key exists otherwise it returns default.

7. How do you loop through both keys and values in a dictionary?  
   `Answer:` for key, value in d.items():
---

### ✏️ Task: Dictionary Practice

```python
# Create a dictionary with keys: 'name', 'age', and 'hobby'.
# Print each key and value in the format "key: value".
dictonary = {"name" : 'Jose', "age" : 21, "hobby" : 'Tennis Player'}
for value in dictonary.items():
   print(key, ':' + str(value))
```

---

## 🧾 Submit Checklist

- [ ] I practiced creating and modifying lists.
- [ ] I understand how tuples are different from lists.
- [ ] I accessed and looped through dictionary items.
