🧠 Section 1: Lists

1. What method adds an item to the end of a list?
Answer: append()

2. How can you remove an item from a list by value?
Answer: remove()

3. What’s the result of this code?

nums = [2, 4, 6]
nums.append(8)
print(nums)

Answer:
[2, 4, 6, 8]

✏️ Task: List Practice (Example Solution)
foods = ["pizza", "sushi", "burger"]

foods.append("pasta")   # add another food
foods.remove("sushi")   # remove one item

print(foods)

['pizza', 'burger', 'pasta']

🔒 Section 2: Tuples

4. What is a key difference between a list and a tuple?
Answer:
Lists are mutable (can be changed), while tuples are immutable (cannot be changed after creation).

5. Can you change the contents of a tuple once it is created? Why or why not?
Answer:
No, because tuples are immutable, meaning their values cannot be modified after they are created.

✏️ Task: Tuple Practice (Example Solution)
numbers = (3, 7, 10)

a, b, c = numbers  # unpacking

print(a)
print(b)
print(c)

3
7
10

🔑 Section 3: Dictionaries

6. What does the .get() method do differently from accessing a key directly?
Answer:
.get() returns None (or a default value) if the key does not exist, instead of raising an error like direct access (dict[key]).

7. How do you loop through both keys and values in a dictionary?
Answer:
Use the .items() method:

for key, value in my_dict.items():
✏️ Task: Dictionary Practice (Example Solution)
person = {
    "name": "Hoang",
    "age": 20,
    "hobby": "gaming"
}

for key, value in person.items():
    print(f"{key}: {value}")

Answer:
name: Hoang
age: 20
hobby: gaming
