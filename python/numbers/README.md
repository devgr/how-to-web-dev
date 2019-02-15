# Numbers and Variables
In this tutorial, you will learn about outputing results, some of the basic math functions in Python, and using variables for storing results.

## The print function
As shown in the "Hello world!" example before, the `print` function outputs text from your program. Try some of these examples. You can copy-paste this code into a file and then run it, like in the "Hello world!" example.
```python
print('This is some text')
print(1)
print('You can output', 'multiple things', 'seperated by commas.')
print(1, 2, 3)
```
Note how you can print text, which is enclosed in `'` quotation marks, or numbers, or both.

## Comments
Along with your code, you can include explanitory comments. Comments make it easier for other people to read your code.
```python
# Anything after a # symbol is a comment.
# The next line of code outputs a message.
print('This is some text')
```

## Variables
Variables let you temporarily store a value. Here is a simple example to try:
```python
a = 42
print(a)
```
The number `42` was output because the variable `a` contained that number.

## Math operators
Python has operators for addition `+`, subtraction `-`, multiplication `*`, and division `/`, a lot like a calculator. Try running each of these examples and experiment with changing them.
```python
a = 2 + 2
print(a)
# The number 4 will be output.
```

```python
a = 3
b = 2
c = a + b # You can do math with variables! Very helpful.
print(c)
# The number 5 will be output.
```

```python
answer = 45 - 3
print(answer) # 42
print(45 - 3) # This also outputs 42
```

Negative numbers work like normal:
```python
a = -5
b = 6 + a
print(b) # 1
```

Multiplication and division happen before addition and subtraction:
```python
answer = 2 + 5 * 3
print(answer) # 17
example = 20 / 2 - 1
print(example) # 9.0
```

Operations inside parenthesis are done first:
```python
answer = 5 * (3 + 3)
print(answer) # 30
# You can use a previous result to do more calculations
another = answer + 1
print(another) # 31
```

You can even use variables multiple times:
```python
a = 1
a = a + 1
# a is now 2.
a = a + a
# a is now 4.

b = 1
# There's a shortcut for doing b = b + 1:
b += 1
# b is now 2.

# There's a similar shortcut for subtraction
b -= 2
# b is now 0.
```

Numbers with decimals work similarly:
```python
pi = 3.14159
radius = 2.5
circumference = 2 * radius * pi
print(circumference) # 15.70795
```

Exponents use the `**` operator:
```python
squared = 5 ** 2 # 25
cubed = 2 ** 3 # 8
```

### Division
Division is a little bit more complicated because there are two different types of numbers in Python: *Integers* and *Floating point numbers*.
- Integers: These are normal, non-decimal numbers such as 0, 234, and -9. An integer is called an *int* for short.
- Floating point numbers: These are numbers that have decimals, such as 1.5, -45.678, and 3.14159. A floating point number is called a *float* for short. Behind the scenes, floats are actually very complicated, and are not always an exact representations of the number.

Because there are two different types of numbers, there are two types of division: integer division and floating point division. The `/` operator does floating point division, so the result will always have a decimal point. For example, `5 / 2` results in `2.5`, and `10 / 2` results in `5.0` (note the .0).

Integer division uses the `//` operator and it results in the nearest whole number, rounded down. For example, `5 // 2` results in `2`, and `10 // 2` results in `5`.

#### Modulo
To confuse things further, there is also the modulo operator, `%`. It's kind of like the remainder in long division; it tells you how far off something is from being evenly divisible. Don't worry if this doesn't quite make sense; it will be revisited later on. Here are some examples:
- `10 % 2` is `0` because 10 is evenly divisble by 2.
- `11 % 2` is `1` because 11 is off by 1 from being divisible by 2.
- `11 % 3` is `2` because 11 is 2 more than 9, which is divisible by 3.

## Next
So far, you've been putting examples in a .py file and running it. Next you'll learn about [interactive Python](/python/interactive/README.md)
