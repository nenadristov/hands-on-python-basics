
# Dictionaries in Python

Dictionaries are an unordered collection of items in Python. Each item is stored as a key-value pair, where the key is a unique identifier, and the value is the data associated with the key. Dictionaries are defined by enclosing key-value pairs in curly braces `{}`.

## Creating Dictionaries

You can create a dictionary by placing key-value pairs inside curly braces, separated by commas. Each key-value pair is separated by a colon `:`.

```python
# Creating a dictionary
student = {
    "name": "John",
    "age": 21,
    "major": "Computer Science"
}
print(student)
```

## Accessing Dictionary Items

You can access dictionary items by referring to their keys.

```python
# Accessing dictionary items
student = {
    "name": "John",
    "age": 21,
    "major": "Computer Science"
}
print(student["name"])  # Output: John
print(student["age"])   # Output: 21
print(student["major"]) # Output: Computer Science
```

## Adding and Updating Items

You can add new items or update existing items in a dictionary by assigning a value to a new or existing key.

```python
# Adding and updating dictionary items
student = {
    "name": "John",
    "age": 21,
    "major": "Computer Science"
}

# Adding a new key-value pair
student["grade"] = "A"
print(student)  
# Output: {'name': 'John', 'age': 21, 'major': 'Computer Science', 'grade': 'A'}

# Updating an existing key-value pair
student["age"] = 22
print(student)  
# Output: {'name': 'John', 'age': 22, 'major': 'Computer Science', 'grade': 'A'}
```

## Removing Items

You can remove items from a dictionary using the `pop()` method, the `del` statement, or the `popitem()` method.

```python
# Removing dictionary items
student = {
    "name": "John",
    "age": 21,
    "major": "Computer Science",
    "grade": "A"
}

# Using pop() method
age = student.pop("age")
print(age)      # Output: 21
print(student)  # Output: {'name': 'John', 'major': 'Computer Science', 'grade': 'A'}

# Using del statement
del student["grade"]
print(student)  # Output: {'name': 'John', 'major': 'Computer Science'}

# Using popitem() method
# Note: popitem() removes and returns the last inserted item
item = student.popitem()
print(item)     # Output: ('major', 'Computer Science')
print(student)  # Output: {'name': 'John'}
```

## Looping Through Dictionaries

You can loop through the keys, values, or key-value pairs in a dictionary using a `for` loop.

```python
# Looping through a dictionary
student = {
    "name": "John",
    "age": 21,
    "major": "Computer Science"
}

# Looping through keys
for key in student:
    print(key)

# Looping through values
for value in student.values():
    print(value)

# Looping through key-value pairs
for key, value in student.items():
    print(f"{key}: {value}")
```

## Conclusion

Dictionaries are a powerful and flexible data structure in Python that allow you to store and manipulate data using key-value pairs. By understanding how to create, access, modify, and use dictionaries effectively, you can manage and organize data efficiently in your Python programs.
