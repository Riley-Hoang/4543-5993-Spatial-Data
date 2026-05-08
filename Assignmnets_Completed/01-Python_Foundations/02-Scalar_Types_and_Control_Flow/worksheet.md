# 📝 Worksheet: 03 - Scalar Types and Control Flow

Use this worksheet to reinforce your understanding of variables, comparisons, and decision logic.

---

## 🧠 Section 1: Scalar Types

1. What is the output of the following code?

```python
x = 10
print(type(x))
```

`Answer:` class int

1. What scalar type would best represent:
   - A person's name: True
   - Their age: True
   - Whether they passed a test: True

---

### ✏️ Task: Type Practice

```python
# Create a variable for each type and print its value and type
# Example: an int, float, str, and bool

num = 10
Utr = 11.72
name = "Rowan" 
is_active = True

print(num, type(num))
print(Utr, type(Utr))
print(name, type(name))
print(is_active, type(is_active))

```

---

## 🔁 Section 2: Comparison Operators

3. What does the `!=` operator mean?

`Answer:` Not Equal to

1. What will the following code print?

```python
a = 5
b = 3
print(a < b or b < 10)
```

`Answer:` True

---

## 🔀 Section 3: Control Flow

5. Write a conditional that prints "Pass" if a grade is >= 70, and "Fail" otherwise.

```python
# Your code:
grade = 75
if grade >= 70:
   print("Pass")
else:
   print("Fail")


```

6. What does `elif` allow you to do?

`Answer:` Let's user check another condition if the first condition is false.

---

### ✏️ Task: Your Turn

Write a program that asks for the weather and prints:
- "Bring sunscreen" if it's sunny
- "Take an umbrella" if it's raining
- "Check the forecast" otherwise


```python
Weather = str(input("Enter if it's sunny or raining, or I don't know: "))

if Weather == "sunny":
   print("Bring sunscreen")
elif Weather == "raining":
   print("Take and umbrella")
else:
   print("Check the forecast")

```