# Conditionals in Python

Conditionals allow your program to make decisions based on certain conditions. In Python, conditionals are implemented using the `if`, `elif`, and `else` statements. These statements enable your program to execute different blocks of code based on the evaluation of Boolean expressions.

## Basic `if` Statement

The `if` statement evaluates a condition (a Boolean expression). If the condition is `True`, the block of code under the `if` statement is executed.

```python
# Basic if statement
age = 18
if age >= 18:
    print("You are an adult.")
```

## if-else Statement
The if-else statement provides an alternative block of code to execute if the condition is False.
```python
# if-else statement
age = 16
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
```
## if-elif-else Statement
The if-elif-else statement allows you to check multiple conditions. The first condition that evaluates to True will have its block executed, and the rest will be skipped.
```python
# if-elif-else statement
age = 20
if age < 13:
    print("You are a child.")
elif 13 <= age < 18:
    print("You are a teenager.")
else:
    print("You are an adult.")
```

## Nested Conditionals
Conditionals can be nested within other conditionals. This allows you to check additional conditions within an already established conditional block.
```python 
# Nested conditionals
age = 20
if age >= 18:
    print("You are an adult.")
    if age >= 65:
        print("You are a senior citizen.")
    else:
        print("You are not a senior citizen.")
else:
    print("You are a minor.")
```

## Logical Operators
Logical operators (and, or, not) are often used in conditional statements to combine multiple conditions.

### Using *and*
The and operator checks if both conditions are True.
```python 
# Using and operator
age = 25
has_id = True
if age >= 18 and has_id:
    print("You are allowed to enter.")
else:
    print("You are not allowed to enter.")
```

### Using *or*
The or operator checks if at least one condition is True. 
```python
# Using or operator
age = 17
has_permission = True
if age >= 18 or has_permission:
    print("You are allowed to enter.")
else:
    print("You are not allowed to enter.")
```
### Using *not*
The not operator inverts the Boolean value of the condition.
# Using not operator
```python
is_raining = False
if not is_raining:
    print("You can go outside without an umbrella.")
else:
    print("You need an umbrella.")
```

## Conclusion
Conditionals are a fundamental aspect of programming that allow you to control the flow of your program based on different conditions. By using if, elif, and else statements along with logical operators, you can create complex decision-making processes in your code. Understanding and utilizing conditionals effectively will help you build more dynamic and responsive programs.