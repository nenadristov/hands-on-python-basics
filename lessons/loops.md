# Loops in Python

Loops are fundamental programming constructs that allow you to execute a block of code multiple times. In Python, the most common types of loops are `for` loops and `while` loops. These loops help in iterating over sequences or executing code until a certain condition is met.

## `for` Loop

The `for` loop is used to iterate over a sequence (such as a list, tuple, dictionary, set, or string) and execute a block of code for each item in the sequence.

### Basic `for` Loop

```python
# Using a for loop to iterate over a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

## Iterating Over a Range
The range() function generates a sequence of numbers, which is often used with for loops. The range() functions generates "array" of numbers starting from 0 to n-1

For example if we specify 5 inside the brackets it will generate array like "0,1,2,3,4"
```python
# Using a for loop with range
for i in range(5): # 
    print(i)
```

## while Loop
The while loop executes a block of code as long as a specified condition is True. It is typically used when the number of iterations is not known beforehand.

### Basic while Loop
```python 
# Using a while loop
count = 0
while count < 5:
    print(count)
    count += 1
```

### Infinite Loop
A while loop can run indefinitely if the condition never becomes False. Ensure to include a terminating condition to avoid infinite loops.
```python
# Infinite loop example
while True:
    print("This will run forever unless stopped.")
    break  # Use break to exit the loop
```

## Loop Control Statements
### break Statement
The break statement is used to exit a loop prematurely.
```python
# Using break in a loop
for i in range(10):
    if i == 5:
        break
    print(i)
```

## Conclusion
Loops are essential for automating repetitive tasks and iterating over sequences. Python's for and while loops provide flexible and powerful ways to execute code multiple times based on conditions or sequences. By mastering loops and their control statements (break), you can write efficient and effective code to handle a wide range of programming tasks.