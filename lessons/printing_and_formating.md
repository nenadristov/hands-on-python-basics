# Printing and Formatting Strings

Printing and formatting strings are fundamental tasks in programming. In Python, there are several ways to print and format strings, allowing for dynamic and readable output.

## Basic Printing

The `print()` function is used to output text to the console. You can print strings directly or print the values of variables.

```python
# Printing a string directly
print("Hello, World!")

# Printing the value of a variable
name = "Alice"
print(name)
```

## String Concatenation
Strings can be concatenated (combined) using the + operator.

```python
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name
print(full_name)
```

## String Formatting Methods
###  Using the format() Method
The format() method allows for inserting variables into strings. Placeholders {} are used to indicate where the variables should be inserted.
```python
name = "Alice"
age = 30
greeting = "My name is {} and I am {} years old.".format(name, age)
print(greeting)
```

### Using F-Strings (Formatted String Literals)
F-strings, introduced in Python 3.6, provide a concise way to include variables in strings. Prefix the string with f and use curly braces {} to embed expressions.
```python
name = "Alice"
age = 30
greeting = f"My name is {name} and I am {age} years old."
print(greeting)
```

## Running a Python script
A python program / script can be run just by running the following command in the terminal
```bash
python <name-of-the-script>.py
# OR
python app.py
```