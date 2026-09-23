# yolo-test
yolo-testing
# 🐍 Python Programs Collection

A comprehensive collection of **Python programs** for beginners, students, interview preparation, competitive programming, and practical learning.

This repository contains programs ranging from **basic Python syntax** to **OOP, data structures, algorithms, file handling, databases, APIs, and practical projects**.

---

## 📚 Table of Contents

1. [Basic Python Programs](#1-basic-python-programs)
2. [Input and Output](#2-input-and-output)
3. [Operators](#3-operators)
4. [Conditional Statements](#4-conditional-statements)
5. [Loops](#5-loops)
6. [Number Programs](#6-number-programs)
7. [Pattern Programs](#7-pattern-programs)
8. [String Programs](#8-string-programs)
9. [List Programs](#9-list-programs)
10. [Tuple Programs](#10-tuple-programs)
11. [Set Programs](#11-set-programs)
12. [Dictionary Programs](#12-dictionary-programs)
13. [Functions](#13-functions)
14. [Recursion](#14-recursion)
15. [Lambda, Map, Filter and Reduce](#15-lambda-map-filter-and-reduce)
16. [Object-Oriented Programming](#16-object-oriented-programming)
17. [Exception Handling](#17-exception-handling)
18. [File Handling](#18-file-handling)
19. [Date and Time](#19-date-and-time)
20. [Regular Expressions](#20-regular-expressions)
21. [Data Structures](#21-data-structures)
22. [Searching and Sorting](#22-searching-and-sorting)
23. [Algorithms](#23-algorithms)
24. [Mathematical Programs](#24-mathematical-programs)
25. [Python Modules](#25-python-modules)
26. [JSON Programs](#26-json-programs)
27. [CSV Programs](#27-csv-programs)
28. [Database Programs](#28-database-programs)
29. [API Programs](#29-api-programs)
30. [NumPy Programs](#30-numpy-programs)
31. [Pandas Programs](#31-pandas-programs)
32. [Matplotlib Programs](#32-matplotlib-programs)
33. [Machine Learning Programs](#33-machine-learning-programs)
34. [Mini Projects](#34-mini-projects)

---

# 1. Basic Python Programs

### 1. Hello World

```python
print("Hello, World!")
```

### 2. Print Your Name

```python
name = "Akash"
print(name)
```

### 3. Print Multiple Values

```python
name = "Akash"
age = 29

print("Name:", name)
print("Age:", age)
```

### 4. Comments

```python
# This is a single-line comment

"""
This is a
multi-line comment
"""
```

---

# 2. Input and Output

### 5. Take String Input

```python
name = input("Enter your name: ")
print("Hello", name)
```

### 6. Take Integer Input

```python
num = int(input("Enter a number: "))
print(num)
```

### 7. Take Float Input

```python
num = float(input("Enter a number: "))
print(num)
```

### 8. Add Two Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum =", a + b)
```

### 9. Swap Two Numbers

```python
a = 10
b = 20

a, b = b, a

print(a, b)
```

---

# 3. Operators

### 10. Arithmetic Operators

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a // b)
print(a % b)
print(a ** b)
```

### 11. Comparison Operators

```python
a = 10
b = 20

print(a == b)
print(a != b)
print(a > b)
print(a < b)
print(a >= b)
print(a <= b)
```

### 12. Logical Operators

```python
a = 10
b = 20

print(a > 5 and b > 10)
print(a > 15 or b > 10)
print(not(a > 5))
```

---

# 4. Conditional Statements

### 13. Check Positive or Negative

```python
num = int(input("Enter number: "))

if num > 0:
    print("Positive")
elif num < 0:
    print("Negative")
else:
    print("Zero")
```

### 14. Check Even or Odd

```python
num = int(input("Enter number: "))

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### 15. Find Largest of Two Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

if a > b:
    print(a)
else:
    print(b)
```

### 16. Find Largest of Three Numbers

```python
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

print(max(a, b, c))
```

### 17. Check Leap Year

```python
year = int(input("Enter year: "))

if year % 400 == 0 or (year % 4 == 0 and year % 100 != 0):
    print("Leap Year")
else:
    print("Not a Leap Year")
```

### 18. Grade Calculator

```python
marks = float(input("Enter marks: "))

if marks >= 90:
    print("A")
elif marks >= 80:
    print("B")
elif marks >= 70:
    print("C")
elif marks >= 60:
    print("D")
else:
    print("F")
```

---

# 5. Loops

### 19. Print 1 to 10

```python
for i in range(1, 11):
    print(i)
```

### 20. Print Even Numbers

```python
for i in range(2, 21, 2):
    print(i)
```

### 21. Print Odd Numbers

```python
for i in range(1, 20, 2):
    print(i)
```

### 22. Multiplication Table

```python
num = int(input("Enter number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
```

### 23. Sum of First N Numbers

```python
n = int(input("Enter n: "))

total = 0

for i in range(1, n + 1):
    total += i

print(total)
```

### 24. While Loop

```python
i = 1

while i <= 10:
    print(i)
    i += 1
```

### 25. Break

```python
for i in range(1, 11):
    if i == 5:
        break
    print(i)
```

### 26. Continue

```python
for i in range(1, 11):
    if i == 5:
        continue
    print(i)
```

---

# 6. Number Programs

### 27. Reverse a Number

```python
num = int(input("Enter number: "))

reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num //= 10

print(reverse)
```

### 28. Palindrome Number

```python
num = int(input("Enter number: "))

original = num
reverse = 0

while num > 0:
    digit = num % 10
    reverse = reverse * 10 + digit
    num //= 10

if original == reverse:
    print("Palindrome")
else:
    print("Not Palindrome")
```

### 29. Count Digits

```python
num = int(input("Enter number: "))

count = 0

while num:
    count += 1
    num //= 10

print(count)
```

### 30. Sum of Digits

```python
num = int(input("Enter number: "))

total = 0

while num:
    total += num % 10
    num //= 10

print(total)
```

### 31. Product of Digits

```python
num = int(input("Enter number: "))

product = 1

while num:
    product *= num % 10
    num //= 10

print(product)
```

### 32. Factorial

```python
n = int(input("Enter number: "))

factorial = 1

for i in range(1, n + 1):
    factorial *= i

print(factorial)
```

### 33. Fibonacci Series

```python
n = int(input("Enter number of terms: "))

a, b = 0, 1

for _ in range(n):
    print(a, end=" ")
    a, b = b, a + b
```

### 34. Prime Number

```python
num = int(input("Enter number: "))

if num < 2:
    print("Not Prime")
else:
    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            print("Not Prime")
            break
    else:
        print("Prime")
```

### 35. Prime Numbers in a Range

```python
start = int(input("Enter start: "))
end = int(input("Enter end: "))

for num in range(start, end + 1):

    if num < 2:
        continue

    for i in range(2, int(num ** 0.5) + 1):
        if num % i == 0:
            break
    else:
        print(num)
```

### 36. Armstrong Number

```python
num = int(input("Enter number: "))

digits = len(str(num))
total = sum(int(digit) ** digits for digit in str(num))

if total == num:
    print("Armstrong Number")
else:
    print("Not Armstrong")
```

### 37. Perfect Number

```python
num = int(input("Enter number: "))

total = 0

for i in range(1, num):
    if num % i == 0:
        total += i

if total == num:
    print("Perfect Number")
else:
    print("Not Perfect")
```

### 38. Strong Number

```python
import math

num = int(input("Enter number: "))

total = sum(math.factorial(int(digit)) for digit in str(num))

if total == num:
    print("Strong Number")
else:
    print("Not Strong")
```

### 39. GCD

```python
import math

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print(math.gcd(a, b))
```

### 40. LCM

```python
import math

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print(math.lcm(a, b))
```

---

# 7. Pattern Programs

### 41. Star Triangle

```python
n = 5

for i in range(1, n + 1):
    print("*" * i)
```

Output:

```text
*
**
***
****
*****
```

### 42. Reverse Triangle

```python
n = 5

for i in range(n, 0, -1):
    print("*" * i)
```

### 43. Number Triangle

```python
n = 5

for i in range(1, n + 1):
    for j in range(1, i + 1):
        print(j, end=" ")
    print()
```

### 44. Pyramid

```python
n = 5

for i in range(1, n + 1):
    print(" " * (n - i) + "*" * (2 * i - 1))
```

### 45. Floyd's Triangle

```python
n = 5
num = 1

for i in range(1, n + 1):
    for j in range(i):
        print(num, end=" ")
        num += 1
    print()
```

---

# 8. String Programs

### 46. Reverse String

```python
text = input("Enter string: ")

print(text[::-1])
```

### 47. Palindrome String

```python
text = input("Enter string: ")

if text == text[::-1]:
    print("Palindrome")
else:
    print("Not Palindrome")
```

### 48. Count Vowels

```python
text = input("Enter string: ")

count = 0

for char in text.lower():
    if char in "aeiou":
        count += 1

print("Vowels:", count)
```

### 49. Count Words

```python
text = input("Enter sentence: ")

print("Words:", len(text.split()))
```

### 50. Count Characters

```python
text = input("Enter string: ")

frequency = {}

for char in text:
    frequency[char] = frequency.get(char, 0) + 1

print(frequency)
```

### 51. Remove Spaces

```python
text = input("Enter string: ")

print(text.replace(" ", ""))
```

### 52. Check Anagram

```python
a = input("Enter first string: ").replace(" ", "").lower()
b = input("Enter second string: ").replace(" ", "").lower()

if sorted(a) == sorted(b):
    print("Anagram")
else:
    print("Not Anagram")
```

### 53. Count Vowels and Consonants

```python
text = input("Enter string: ")

vowels = 0
consonants = 0

for char in text.lower():
    if char.isalpha():
        if char in "aeiou":
            vowels += 1
        else:
            consonants += 1

print("Vowels:", vowels)
print("Consonants:", consonants)
```

---

# 9. List Programs

### 54. Create a List

```python
numbers = [10, 20, 30, 40, 50]

print(numbers)
```

### 55. Find Maximum

```python
numbers = [10, 50, 20, 40, 30]

print(max(numbers))
```

### 56. Find Minimum

```python
numbers = [10, 50, 20, 40, 30]

print(min(numbers))
```

### 57. Find Sum

```python
numbers = [10, 20, 30, 40]

print(sum(numbers))
```

### 58. Remove Duplicates

```python
numbers = [1, 2, 2, 3, 4, 4, 5]

numbers = list(set(numbers))

print(numbers)
```

### 59. Sort List

```python
numbers = [5, 2, 8, 1, 3]

numbers.sort()

print(numbers)
```

### 60. Second Largest

```python
numbers = [10, 20, 50, 30, 40]

unique_numbers = sorted(set(numbers))

print(unique_numbers[-2])
```

### 61. List Comprehension

```python
squares = [x ** 2 for x in range(1, 11)]

print(squares)
```

### 62. Even Numbers Using List Comprehension

```python
numbers = [1, 2, 3, 4, 5, 6]

even = [x for x in numbers if x % 2 == 0]

print(even)
```

---

# 10. Tuple Programs

### 63. Create Tuple

```python
numbers = (10, 20, 30, 40)

print(numbers)
```

### 64. Tuple Unpacking

```python
person = ("Akash", 29, "Developer")

name, age, profession = person

print(name)
print(age)
print(profession)
```

### 65. Convert Tuple to List

```python
data = (1, 2, 3, 4)

print(list(data))
```

---

# 11. Set Programs

### 66. Create Set

```python
numbers = {1, 2, 3, 4}

print(numbers)
```

### 67. Union

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a | b)
```

### 68. Intersection

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a & b)
```

### 69. Difference

```python
a = {1, 2, 3}
b = {3, 4, 5}

print(a - b)
```

---

# 12. Dictionary Programs

### 70. Create Dictionary

```python
student = {
    "name": "Akash",
    "age": 29,
    "course": "BCA"
}

print(student)
```

### 71. Access Dictionary Values

```python
print(student["name"])
```

### 72. Add Dictionary Value

```python
student["city"] = "Alipurduar"

print(student)
```

### 73. Iterate Dictionary

```python
for key, value in student.items():
    print(key, ":", value)
```

### 74. Word Frequency

```python
text = input("Enter text: ")

words = text.split()
frequency = {}

for word in words:
    frequency[word] = frequency.get(word, 0) + 1

print(frequency)
```

---

# 13. Functions

### 75. Simple Function

```python
def greet():
    print("Hello Python")

greet()
```

### 76. Function with Arguments

```python
def add(a, b):
    return a + b

print(add(10, 20))
```

### 77. Default Arguments

```python
def greet(name="User"):
    print("Hello", name)

greet()
greet("Akash")
```

### 78. Keyword Arguments

```python
def student(name, age):
    print(name, age)

student(age=29, name="Akash")
```

### 79. Variable Arguments

```python
def total(*numbers):
    return sum(numbers)

print(total(10, 20, 30, 40))
```

---

# 14. Recursion

### 80. Factorial Using Recursion

```python
def factorial(n):

    if n == 0:
        return 1

    return n * factorial(n - 1)


print(factorial(5))
```

### 81. Fibonacci Using Recursion

```python
def fibonacci(n):

    if n <= 1:
        return n

    return fibonacci(n - 1) + fibonacci(n - 2)


print(fibonacci(10))
```

---

# 15. Lambda, Map, Filter and Reduce

### 82. Lambda Function

```python
square = lambda x: x * x

print(square(5))
```

### 83. Map

```python
numbers = [1, 2, 3, 4, 5]

squares = list(map(lambda x: x ** 2, numbers))

print(squares)
```

### 84. Filter

```python
numbers = [1, 2, 3, 4, 5, 6]

even = list(filter(lambda x: x % 2 == 0, numbers))

print(even)
```

### 85. Reduce

```python
from functools import reduce

numbers = [1, 2, 3, 4, 5]

result = reduce(lambda x, y: x + y, numbers)

print(result)
```

---

# 16. Object-Oriented Programming

### 86. Create Class

```python
class Student:

    def __init__(self, name, age):
        self.name = name
        self.age = age

    def display(self):
        print(self.name, self.age)


student = Student("Akash", 29)

student.display()
```

### 87. Inheritance

```python
class Animal:

    def speak(self):
        print("Animal speaks")


class Dog(Animal):

    def bark(self):
        print("Dog barks")


dog = Dog()

dog.speak()
dog.bark()
```

### 88. Encapsulation

```python
class Bank:

    def __init__(self):
        self.__balance = 1000

    def get_balance(self):
        return self.__balance


account = Bank()

print(account.get_balance())
```

### 89. Polymorphism

```python
class Dog:

    def sound(self):
        print("Bark")


class Cat:

    def sound(self):
        print("Meow")


for animal in [Dog(), Cat()]:
    animal.sound()
```

---

# 17. Exception Handling

### 90. Try Except

```python
try:
    a = int(input("Enter number: "))
    b = int(input("Enter number: "))

    print(a / b)

except ZeroDivisionError:
    print("Cannot divide by zero")

except ValueError:
    print("Invalid input")
```

### 91. Finally

```python
try:
    print(10 / 2)

except Exception as e:
    print(e)

finally:
    print("Program completed")
```

### 92. Raise Exception

```python
age = int(input("Enter age: "))

if age < 18:
    raise ValueError("Age must be 18 or above")
```

---

# 18. File Handling

### 93. Write File

```python
with open("data.txt", "w") as file:
    file.write("Hello Python")
```

### 94. Read File

```python
with open("data.txt", "r") as file:
    data = file.read()

print(data)
```

### 95. Append File

```python
with open("data.txt", "a") as file:
    file.write("\nNew line")
```

### 96. Count Lines

```python
with open("data.txt") as file:
    lines = file.readlines()

print("Lines:", len(lines))
```

---

# 19. Date and Time

### 97. Current Date and Time

```python
from datetime import datetime

print(datetime.now())
```

### 98. Current Date

```python
from datetime import date

print(date.today())
```

### 99. Calculate Age

```python
from datetime import date

birth_year = int(input("Enter birth year: "))

current_year = date.today().year

print(current_year - birth_year)
```

---

# 20. Regular Expressions

### 100. Find Email

```python
import re

text = "Contact: example@gmail.com"

email = re.findall(r'[\w.-]+@[\w.-]+\.\w+', text)

print(email)
```

### 101. Find Numbers

```python
import re

text = "Python 3 is released in 1991."

numbers = re.findall(r'\d+', text)

print(numbers)
```

---

# 21. Data Structures

## Stack

### 102. Stack Using List

```python
stack = []

stack.append(10)
stack.append(20)
stack.append(30)

print(stack.pop())
print(stack)
```

## Queue

### 103. Queue Using Deque

```python
from collections import deque

queue = deque()

queue.append(10)
queue.append(20)
queue.append(30)

print(queue.popleft())
print(queue)
```

## Linked List

### 104. Simple Linked List

```python
class Node:

    def __init__(self, data):
        self.data = data
        self.next = None


first = Node(10)
second = Node(20)

first.next = second

print(first.data)
print(first.next.data)
```

---

# 22. Searching and Sorting

### 105. Linear Search

```python
numbers = [10, 20, 30, 40, 50]

target = 30

for i, value in enumerate(numbers):

    if value == target:
        print("Found at index", i)
        break
```

### 106. Binary Search

```python
numbers = [10, 20, 30, 40, 50]

target = 40

low = 0
high = len(numbers) - 1

while low <= high:

    mid = (low + high) // 2

    if numbers[mid] == target:
        print("Found")
        break

    elif numbers[mid] < target:
        low = mid + 1

    else:
        high = mid - 1
```

### 107. Bubble Sort

```python
numbers = [5, 3, 8, 4, 2]

n = len(numbers)

for i in range(n):

    for j in range(0, n - i - 1):

        if numbers[j] > numbers[j + 1]:
            numbers[j], numbers[j + 1] = numbers[j + 1], numbers[j]

print(numbers)
```

### 108. Selection Sort

```python
numbers = [5, 3, 8, 4, 2]

for i in range(len(numbers)):

    minimum = i

    for j in range(i + 1, len(numbers)):

        if numbers[j] < numbers[minimum]:
            minimum = j

    numbers[i], numbers[minimum] = numbers[minimum], numbers[i]

print(numbers)
```

### 109. Insertion Sort

```python
numbers = [5, 3, 8, 4, 2]

for i in range(1, len(numbers)):

    key = numbers[i]
    j = i - 1

    while j >= 0 and numbers[j] > key:
        numbers[j + 1] = numbers[j]
        j -= 1

    numbers[j + 1] = key

print(numbers)
```

---

# 23. Algorithms

### 110. Maximum Element

```python
numbers = [10, 30, 20, 50, 40]

maximum = numbers[0]

for number in numbers:
    if number > maximum:
        maximum = number

print(maximum)
```

### 111. Minimum Element

```python
numbers = [10, 30, 20, 50, 40]

minimum = numbers[0]

for number in numbers:
    if number < minimum:
        minimum = number

print(minimum)
```

### 112. Two Sum

```python
numbers = [2, 7, 11, 15]
target = 9

for i in range(len(numbers)):

    for j in range(i + 1, len(numbers)):

        if numbers[i] + numbers[j] == target:
            print(i, j)
```

### 113. Duplicate Elements

```python
numbers = [1, 2, 3, 2, 4, 1]

duplicates = []

for number in numbers:

    if numbers.count(number) > 1 and number not in duplicates:
        duplicates.append(number)

print(duplicates)
```

---

# 24. Mathematical Programs

### 114. Celsius to Fahrenheit

```python
celsius = float(input("Enter Celsius: "))

fahrenheit = (celsius * 9 / 5) + 32

print(fahrenheit)
```

### 115. Fahrenheit to Celsius

```python
fahrenheit = float(input("Enter Fahrenheit: "))

celsius = (fahrenheit - 32) * 5 / 9

print(celsius)
```

### 116. Simple Interest

```python
principal = float(input("Principal: "))
rate = float(input("Rate: "))
time = float(input("Time: "))

interest = (principal * rate * time) / 100

print("Simple Interest:", interest)
```

### 117. Compound Interest

```python
principal = float(input("Principal: "))
rate = float(input("Rate: "))
time = float(input("Time: "))

amount = principal * (1 + rate / 100) ** time

print("Amount:", amount)
```

### 118. Area of Circle

```python
import math

radius = float(input("Enter radius: "))

area = math.pi * radius ** 2

print("Area:", area)
```

### 119. Quadratic Equation

```python
import math

a = float(input("a: "))
b = float(input("b: "))
c = float(input("c: "))

discriminant = b ** 2 - 4 * a * c

if discriminant >= 0:

    x1 = (-b + math.sqrt(discriminant)) / (2 * a)
    x2 = (-b - math.sqrt(discriminant)) / (2 * a)

    print(x1, x2)

else:
    print("Complex roots")
```

---

# 25. Python Modules

### 120. Import Math

```python
import math

print(math.sqrt(25))
print(math.factorial(5))
print(math.pi)
```

### 121. Random Number

```python
import random

number = random.randint(1, 100)

print(number)
```

### 122. Random Choice

```python
import random

items = ["Python", "Java", "C++", "JavaScript"]

print(random.choice(items))
```

---

# 26. JSON Programs

### 123. Python Dictionary to JSON

```python
import json

student = {
    "name": "Akash",
    "age": 29
}

data = json.dumps(student)

print(data)
```

### 124. JSON to Dictionary

```python
import json

data = '{"name": "Akash", "age": 29}'

student = json.loads(data)

print(student["name"])
```

---

# 27. CSV Programs

### 125. Write CSV

```python
import csv

with open("students.csv", "w", newline="") as file:

    writer = csv.writer(file)

    writer.writerow(["Name", "Age"])
    writer.writerow(["Akash", 29])
```

### 126. Read CSV

```python
import csv

with open("students.csv") as file:

    reader = csv.reader(file)

    for row in reader:
        print(row)
```

---

# 28. Database Programs

## SQLite

### 127. Create Database

```python
import sqlite3

connection = sqlite3.connect("students.db")

cursor = connection.cursor()

cursor.execute("""
CREATE TABLE IF NOT EXISTS students(
    id INTEGER PRIMARY KEY,
    name TEXT,
    age INTEGER
)
""")

connection.commit()
connection.close()
```

### 128. Insert Data

```python
import sqlite3

connection = sqlite3.connect("students.db")

cursor = connection.cursor()

cursor.execute(
    "INSERT INTO students(name, age) VALUES (?, ?)",
    ("Akash", 29)
)

connection.commit()
connection.close()
```

### 129. Select Data

```python
import sqlite3

connection = sqlite3.connect("students.db")

cursor = connection.cursor()

cursor.execute("SELECT * FROM students")

for row in cursor.fetchall():
    print(row)

connection.close()
```

---

# 29. API Programs

### 130. GET API Request

```python
import requests

url = "https://jsonplaceholder.typicode.com/posts"

response = requests.get(url)

print(response.status_code)
print(response.json())
```

### 131. POST API Request

```python
import requests

url = "https://jsonplaceholder.typicode.com/posts"

data = {
    "title": "Python",
    "body": "Learning API",
    "userId": 1
}

response = requests.post(url, json=data)

print(response.status_code)
print(response.json())
```

---

# 30. NumPy Programs

Install NumPy:

```bash
pip install numpy
```

### 132. NumPy Array

```python
import numpy as np

numbers = np.array([1, 2, 3, 4, 5])

print(numbers)
```

### 133. NumPy Operations

```python
import numpy as np

numbers = np.array([1, 2, 3, 4, 5])

print(numbers + 10)
print(numbers * 2)
print(numbers.mean())
print(numbers.max())
print(numbers.min())
```

### 134. NumPy Matrix

```python
import numpy as np

matrix = np.array([
    [1, 2],
    [3, 4]
])

print(matrix)
```

---

# 31. Pandas Programs

Install Pandas:

```bash
pip install pandas
```

### 135. Create DataFrame

```python
import pandas as pd

data = {
    "Name": ["Akash", "Rahul", "Amit"],
    "Age": [29, 25, 28]
}

df = pd.DataFrame(data)

print(df)
```

### 136. Read CSV Using Pandas

```python
import pandas as pd

df = pd.read_csv("students.csv")

print(df)
```

### 137. DataFrame Statistics

```python
print(df.describe())
```

### 138. Filter Data

```python
result = df[df["Age"] > 25]

print(result)
```

### 139. Missing Values

```python
print(df.isnull().sum())
```

---

# 32. Matplotlib Programs

Install:

```bash
pip install matplotlib
```

### 140. Line Chart

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 30, 25]

plt.plot(x, y)

plt.title("Line Chart")
plt.xlabel("X")
plt.ylabel("Y")

plt.show()
```

### 141. Bar Chart

```python
import matplotlib.pyplot as plt

names = ["A", "B", "C"]
marks = [80, 90, 75]

plt.bar(names, marks)

plt.show()
```

### 142. Pie Chart

```python
import matplotlib.pyplot as plt

labels = ["Python", "Java", "C++"]
values = [50, 30, 20]

plt.pie(values, labels=labels, autopct="%1.1f%%")

plt.show()
```

---

# 33. Machine Learning Programs

Install common ML libraries:

```bash
pip install numpy pandas scikit-learn matplotlib
```

### 143. Train-Test Split

```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(
    X,
    y,
    test_size=0.2,
    random_state=42
)
```

### 144. Linear Regression

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()

model.fit(X_train, y_train)

predictions = model.predict(X_test)

print(predictions)
```

### 145. Decision Tree

```python
from sklearn.tree import DecisionTreeRegressor

model = DecisionTreeRegressor(random_state=1)

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

### 146. Random Forest

```python
from sklearn.ensemble import RandomForestRegressor

model = RandomForestRegressor(
    random_state=1
)

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

### 147. Classification

```python
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier(
    random_state=42
)

model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

### 148. Accuracy

```python
from sklearn.metrics import accuracy_score

accuracy = accuracy_score(y_test, predictions)

print("Accuracy:", accuracy)
```

### 149. Mean Absolute Error

```python
from sklearn.metrics import mean_absolute_error

mae = mean_absolute_error(y_test, predictions)

print("MAE:", mae)
```

---

# 34. Mini Projects

The following projects can be added to this repository as separate folders.

| #  | Project                     | Difficulty   |
| -- | --------------------------- | ------------ |
| 1  | Calculator                  | Beginner     |
| 2  | Number Guessing Game        | Beginner     |
| 3  | Rock Paper Scissors         | Beginner     |
| 4  | Quiz Application            | Beginner     |
| 5  | Password Generator          | Beginner     |
| 6  | Digital Clock               | Beginner     |
| 7  | To-Do List                  | Beginner     |
| 8  | Contact Book                | Beginner     |
| 9  | Student Management System   | Intermediate |
| 10 | Library Management System   | Intermediate |
| 11 | Bank Management System      | Intermediate |
| 12 | Expense Tracker             | Intermediate |
| 13 | Weather Application         | Intermediate |
| 14 | URL Shortener               | Intermediate |
| 15 | Web Scraper                 | Intermediate |
| 16 | REST API                    | Intermediate |
| 17 | Blog Application            | Intermediate |
| 18 | E-Commerce Application      | Advanced     |
| 19 | Face Detection              | Advanced     |
| 20 | Chat Application            | Advanced     |
| 21 | Machine Learning Prediction | Advanced     |
| 22 | Stock/Market Prediction     | Advanced     |
| 23 | Recommendation System       | Advanced     |
| 24 | Image Classification        | Advanced     |
| 25 | NLP Sentiment Analysis      | Advanced     |

---

# 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/python-programs.git
```

Go to the project:

```bash
cd python-programs
```

Run a Python file:

```bash
python filename.py
```

For Windows:

```bash
py filename.py
```

---

# 📦 Recommended Folder Structure

```text
python-programs/
│
├── README.md
│
├── 01_basics/
├── 02_input_output/
├── 03_operators/
├── 04_conditionals/
├── 05_loops/
├── 06_numbers/
├── 07_patterns/
├── 08_strings/
├── 09_lists/
├── 10_tuples/
├── 11_sets/
├── 12_dictionaries/
├── 13_functions/
├── 14_recursion/
├── 15_lambda/
├── 16_oop/
├── 17_exceptions/
├── 18_file_handling/
├── 19_datetime/
├── 20_regex/
├── 21_data_structures/
├── 22_searching_sorting/
├── 23_algorithms/
├── 24_mathematics/
├── 25_modules/
├── 26_json/
├── 27_csv/
├── 28_database/
├── 29_api/
├── 30_numpy/
├── 31_pandas/
├── 32_matplotlib/
├── 33_machine_learning/
│
└── 34_projects/
    ├── calculator/
    ├── quiz/
    ├── todo/
    ├── expense_tracker/
    └── student_management/
```

---

# 🎯 Learning Roadmap

```text
Python Basics
     ↓
Variables & Data Types
     ↓
Operators
     ↓
Conditional Statements
     ↓
Loops
     ↓
Strings
     ↓
Lists / Tuples / Sets / Dictionaries
     ↓
Functions
     ↓
Recursion
     ↓
OOP
     ↓
Exception Handling
     ↓
File Handling
     ↓
Modules & Packages
     ↓
Data Structures & Algorithms
     ↓
NumPy
     ↓
Pandas
     ↓
Matplotlib
     ↓
SQL / Databases
     ↓
APIs
     ↓
Machine Learning
     ↓
Projects
```

---

# 🧑‍💻 Who Is This Repository For?

This repository is useful for:

* 🎓 BCA / MCA students
* 🐍 Python beginners
* 👨‍💻 Software developers
* 🤖 Machine Learning beginners
* 📊 Data Science learners
* 💼 Interview preparation
* 🏆 Competitive programming
* 🧪 Programming lab practice
* 👨‍🏫 Teachers and trainers
* 📚 Python course assignments

---

# ⭐ Topics Covered

```text
✓ Python Basics
✓ Variables
✓ Data Types
✓ Operators
✓ Input / Output
✓ Conditions
✓ Loops
✓ Numbers
✓ Strings
✓ Lists
✓ Tuples
✓ Sets
✓ Dictionaries
✓ Functions
✓ Recursion
✓ Lambda
✓ Map / Filter / Reduce
✓ OOP
✓ Exception Handling
✓ File Handling
✓ Regular Expressions
✓ Date & Time
✓ Stack
✓ Queue
✓ Linked List
✓ Searching
✓ Sorting
✓ Algorithms
✓ JSON
✓ CSV
✓ SQLite
✓ REST APIs
✓ NumPy
✓ Pandas
✓ Matplotlib
✓ Machine Learning
✓ Mini Projects
```

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new branch.

```bash
git checkout -b feature/new-program
```

3. Add your Python program.
4. Commit your changes.

```bash
git add .
git commit -m "Add new Python program"
```

5. Push the branch.

```bash
git push origin feature/new-program
```

6. Create a Pull Request.

---

# 📄 License

This project is open source and available under the **MIT License**.

---

# ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub.

**Happy Coding! 🐍💻**
