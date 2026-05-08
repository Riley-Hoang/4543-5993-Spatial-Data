# 📝 Worksheet: 04 - Loops and Iteration

Practice and reflect on how loops work in Python.

---

## 🔁 Section 1: For Loops

1. What does `range(5)` produce?

`Answer:` 0,1,2,3,4

1. Write a `for` loop that prints numbers 1 to 10, but skips 5.

```python
# Your code:
for i in range(1,11):
    if i == 5:
        continue
    print(i)
```

---

## 🔁 Section 2: While Loops

3. What’s the difference between a `for` loop and a `while` loop?

`Answer:` *Repeats the items in a sequence and while executes only if the condition is true.*

1. What happens if a `while` loop's condition never becomes `False`?

`Answer:` *It stops the loop*

---

### ✏️ Task: Countdown with While

```python
# Use a while loop to count down from 5 to 1.
counter = 1
while counter >= 1:
    print('Count:', counter)
    counter -= 1

```

---

## 📁 Section 3: File Reading and `with`

5. What does the `with` statement do when opening a file?

`Answer:` *The with statement opens a file and closes it automatically when done.*

1. How do you loop over each line in a file?

`Answer:` *using the "for line in file"*

---

### ✏️ Task: File Filter

Write code that prints only the lines in a file that contain the word `"error"`.

```python
# Your code here
with open("notes.txt", "r") as file:
    for line in file:
        if "error" in line:
            print(line.strip())

```
