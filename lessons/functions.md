
# Functions in Python

Functions are blocks of code that perform a specific task and can be reused throughout a program. Functions help in organizing code, improving readability, and reducing redundancy. In Python, functions are defined using the `def` keyword.

## Defining a Function

You can define a function using the `def` keyword, followed by the function name and parentheses containing any parameters.

```python
# Defining a function
def greet():
    print("Hello, World!")

# Calling the function
greet()  # Output: Hello, World!
```

## Function Parameters

Functions can accept parameters (arguments) that allow you to pass values into the function. Parameters are specified within the parentheses in the function definition.

```python
# Function with parameters
def greet(name):
    print(f"Hello, {name}!")

# Calling the function with an argument
greet("Alice")  # Output: Hello, Alice!
```

## Default Parameters

You can provide default values for parameters. If an argument is not provided, the default value is used.

```python
# Function with default parameters
def greet(name="Guest"):
    print(f"Hello, {name}!")

# Calling the function without an argument
greet()  # Output: Hello, Guest!

# Calling the function with an argument
greet("Bob")  # Output: Hello, Bob!
```

## Returning Values

Functions can return values using the `return` statement. The returned value can be stored in a variable or used in expressions.

```python
# Function that returns a value
def add(a, b):
    return a + b

# Calling the function and storing the result
result = add(3, 5)
print(result)  # Output: 8
```

## Multiple Return Values

Functions can return multiple values as a tuple.

```python
# Function that returns multiple values
def get_person():
    name = "Alice"
    age = 30
    return name, age

# Calling the function and unpacking the result
name, age = get_person()
print(name)  # Output: Alice
print(age)   # Output: 30
```


## Function Documentation

You can add a documentation string (docstring) to a function to describe its purpose. Docstrings are written as the first statement in the function body and enclosed in triple quotes.

```python
# Function with a docstring
def greet(name):
    """
    This function greets the person whose name is passed as an argument.
    """
    print(f"Hello, {name}!")

# Accessing the docstring
print(greet.__doc__)
```

## Conclusion

Functions are essential building blocks in Python that help in organizing code, improving readability, and promoting code reuse. By defining functions, using parameters, returning values, and leveraging advanced features like variable-length arguments and lambda functions, you can create efficient and modular programs.