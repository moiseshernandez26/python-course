# Let's start with a simple example of hello world
```python
print("Hello World")
```

## Variables
```python
# Variables are used to store data
# Python is a dynamically typed language
# This means that you don't need to specify the type of the variable
# Python will automatically assign the type based on the value assigned to it
language = "Python"
version = 3.8
```

## Data Types
```python
# Python has the following data types
# int, float, str, bool, list, tuple, set, dict, None
# You can check the type of a variable using the type() function
print(type(language))
print(type(version))
```

## Operators
```python
# Python has the following operators
# Arithmetic: +, -, *, /, //, %, **
# Comparison: ==, !=, >, <, >=, <=
# Logical: and, or, not
# Bitwise: &, |, ^, ~, <<, >>

# Arithmetic
print(2 + 3)
print(2 - 3)
print(2 * 3)
print(2 / 3)
print(2 // 3)
print(2 % 3)
print(2 ** 3)

# Comparison
print(2 == 3)
print(2 != 3)
print(2 > 3)
print(2 < 3)
print(2 >= 3)
print(2 <= 3)

# Logical
print(True and False)
print(True or False)
print(not True)

# Bitwise
print(2 & 3)
print(2 | 3)
print(2 ^ 3)
print(~2)
print(2 << 3)
print(2 >> 3)
```

## Conditional Statements
```python
# Conditional statements are used to execute a block of code based on a condition
# Python has the following conditional statements
# if, elif, else

# if
if 2 > 3:
    print("2 is greater than 3")

# if else
if 2 > 3:
    print("2 is greater than 3")
else:
    print("2 is not greater than 3")

# if elif else
if 2 > 3:
    print("2 is greater than 3")
elif 2 < 3:
    print("2 is less than 3")
else:
    print("2 is equal to 3")
```

## Loops
```python
# Loops are used to execute a block of code multiple times
# Python has the following loops
# for, while

# for
for i in range(5):
    print(i)

# while
i = 0
while i < 5:
    print(i)
    i += 1
```

## Functions
```python
# Functions are used to group a set of statements together to perform a specific task
# Python has the following functions
# print(), input(), type(), range(), len(), int(), float(), str(), bool(), list(), tuple(), set(), dict(), sum(), min(), max(), abs(), pow(), round(), sorted(), reversed(), zip(), map(), filter(), reduce()

# def keyword is used to define a function
def add(x, y):
    return x + y

print(add(2, 3))

# print()
print("Hello World")

# input()
name = input("Enter your name: ")
print("Hello", name)

# type()
print(type(2))

# range()
for i in range(5):
    print(i)

# len()
print(len("Hello World"))

# int()
print(int("2"))

# float()
print(float("2.5"))

# str()
print(str(2))

# bool()
print(bool(2))

# list()
print(list("Hello World"))

# tuple()
print(tuple("Hello World"))

# set()
print(set("Hello World"))

# dict()
print(dict(a=1, b=2))

# sum()
print(sum([1, 2, 3]))

# min()
print(min([1, 2, 3]))

# max()
print(max([1, 2, 3]))

# abs()
print(abs(-2))

# pow()
print(pow(2, 3))

# round()
print(round(2.5))

# sorted()
print(sorted([3, 2, 1]))

# reversed()
print(list(reversed([1, 2, 3])))
print("".join(reversed("Hello World")))

# zip()
print(list(zip([1, 2, 3], [4, 5, 6])))
print(list(zip([1, 2, 3], [4, 5, 6], [7, 8, 9])))

# map()
print(list(map(lambda x: x * 2, [1, 2, 3])))
print(list(map(lambda x, y: x + y, [1, 2, 3], [4, 5, 6])))

# filter()
print(list(filter(lambda x: x % 2 == 0, [1, 2, 3])))
print(list(filter(lambda x, y: x + y > 5, [1, 2, 3], [4, 5, 6])))

```

## Dictionary
```python
# Dictionary is a collection of key-value pairs
person = {
    "name": "John",
    "age": 36,
    "country": "Norway"
}

# Accessing items
print(person["name"])
print(person.get("name"))

# Changing values
person["name"] = "Jane"
print(person)

# Looping through a dictionary
for key in person:
    print(key, person[key])

# Adding items
person["city"] = "Oslo"
print(person)

# Removing items
person.pop("city")
print(person)

# Copying a dictionary
person2 = person.copy()
print(person2)

# Nested dictionaries
person = {
    "name": "John",
    "age": 36,
    "country": "Norway",
    "address": {
        "street": "Oslo Street",
        "city": "Oslo",
        "country": "Norway"
    }
}
print(person["address"]["city"])
```