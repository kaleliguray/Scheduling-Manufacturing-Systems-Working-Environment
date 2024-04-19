# 📚 Scheduling Manufacturing Systems 📚

* <p>First of all, this repository is about the lecture that was given during my master's education at Munich Technical University.</p>

* <p>The repository serves as a comprehensive resource for the Scheduling Manufacturing Systems Lecture, utilizing Python as the primary programming language along with the Gurobi Optimizer for mathematical optimization. Its purpose is to study and analyze manufacturing systems efficiently, being a resource for the lecture.</p>

* <p>By integrating the powerful optimization capabilities of Gurobi with Python, learners can explore various scheduling techniques and gain insights into optimizing manufacturing processes. Through a collection of Python scripts, libraries, and documentation, users can delve deeper into the complexities of manufacturing systems, and produce a solution to tackle complex challenges in production scheduling by using both Python and Gurobi Optimizer to.</p>

* <p>Overall, Whether for academic learning or practical application, this repository aims to empower users with the examples and explanations they need to cover and be a resource for scheduling manufacturing systems.</p>

## Table of Contents 📝
- [Getting Started](#getting-started)
  - [Prerequisites](##prerequisites--)
  - [Installation](#installation)
- [Python](#python)
  - [Introduction](#introdution)
  - [String, Print, Type And Comment](#string-print-type-and-comment)
  - [Integers and Floats](#integers-and-floats)
  - [Variable Assignment And Mathematical Operations](#variable-assignment-and-mathematical-operations)
  - [Type Casting And Concatenation](#type-casting-and-concatenation)
  - [List](#list)
  - [Dictionaries](#dictionaries)
  - [Sets and Tuples](#sets-and-tuples)
  - [Loops and Branching](#loops-and-branching)
- [Usage & Contributing](#usage--contributing)
- [License](#license)
- [Resources](#resources)

## Getting Started 🏁

<p>Knowledge about supply chain and production management through quantitative methods. Prerequisites include "Production and Logistics" and "Management Science" modules or equivalent courses at other universities. Furthermore, some familiarity with basic programming, preferably with Python, is highly advised.</p>

### Prerequisites 🎒

- For IDEA: PyCharm IDEA || Anaconda || Google colab
- Language: Python
- Extension: Gurobi Optimizer

### Installation 

<ol type="1">
  <li>Pyhton Installation path - please follow <a href="https://www.python.org/downloads/">download link</a></li>
  <li>Gurobi Optimizer - for Mathematical optimization in Python - installation path: <a href="https://support.gurobi.com/hc/en-us/articles/4534161999889-How-do-I-install-Gurobi-Optimizer">download link</a></li>
  <li> Google colab - can be preferred at the beginning of the progress <a href="https://colab.research.google.com/">usage link - online</a></li>
  <li>Anaconda Installation <a href="https://docs.anaconda.com/free/anaconda/install/index.html">download link</a></li>
  <li>PyCharm - The Python IDE for data science and web development - installation path: <a href="https://www.jetbrains.com/pycharm/download/?section=mac">download link</a></li>
</ol>
<br>
<ul>
  <li>Clone the repository: git clone https://github.com/kaleliguray/Scheduling-Manufacturing-Systems-Working-Environment.git</li>
  <li>Navigate to the project folder: cd your-repo</li>
  <li>Install dependencies: npm install or pip install -r requirements.txt</li>
</ul>

## Python

### Introduction

* Python is a high-level programming language known for its simplicity and readability. It was created by Guido van Rossum and first released in 1991. Python emphasizes code readability and simplicity, making it an excellent choice for beginners and experienced programmers alike.

* Python supports multiple programming paradigms, including procedural, object-oriented, and functional programming. It has a large standard library that provides tools and modules for various tasks, from web development and data analysis to artificial intelligence and scientific computing.

* One of Python's key features is its indentation-based syntax, which enforces code readability and reduces the need for excessive punctuation. This feature makes Python code visually consistent and easier to understand.

* Python's versatility and ease of use have contributed to its widespread adoption across industries and domains, making it one of the most popular programming languages in the world.

<img src="https://miro.medium.com/v2/resize:fit:1400/format:webp/1*QfI8H_8HplGa1v9IrrWjBA.png" alt="Resource by Shawn Ren - Medium Page - Learn about Python 3 data types"/>

<a href="https://medium.com/@shawnren527/learn-about-python-3-data-types-numbers-and-strings-76c75a917c9b">Resource by Shawn Ren - Medium Page - Learn about Python 3 data types</a>

### String, Print, Type And Comment

<ul>
  <li>Character collections known as strings are used to depict a character sequence.</li>
  <li>Quote marks, either single or double, are used to represent strings.</li>
  <li>The print() method in Python is used to print text, such as a string or number, to the screen.</li>
  <li>The type function can be used to display an object's type.</li>
  <li>In Python, comments are denoted by the hash symbol (#) and allow programmers to annotate their code for clarity or documentation. They are ignored by the Python interpreter during execution, making them useful for providing context or explanations within the code.</li>
</ul>

~~~
# Define a string variable
my_string = "Hello, world!"

# Print the string
print(my_string)

# Check the type of the variable
print(type(my_string))
~~~
___
~~~
Hello, world!
<class 'str'>
~~~

### Integers And Floats

<ul>
  <li>Python has two built-in methods for representing numbers: integer and float.</li>
  <li>Decimal numbers are represented by floating points.</li>
</ul>

~~~
# Integer example
my_integer = 10
print("Integer example:", my_integer)

# Float example
my_float = 3.14
print("Float example:", my_float)
~~~
___
~~~
Integer example: 10
Float example: 3.14
~~~

### Variable Assignment And Mathematical Operations

<ul>
  <li>Variables are identifiers that refer to a specific value.</li>
  <li>You can assign values to variables using the assignment operator (=).</li>
  <li>In addition to common arithmetic operations, such as addition and subtraction, there's another useful operation called the modulo operator. It calculates the remainder when dividing two positive integers, which is frequently used in programming.</li>
</ul>

~~~
# Variable assignment
x = 10

# Assigning a value to a variable
y = 5

# Modulo operator example
result = 10 % 3  # This will return 1 since 10 divided by 3 leaves a remainder of 1
~~~


### Type Casting And Concatenation

<ul>
  <li>You can change the type of a variable to another type using specific functions.</li>
  <li>Concatenation refers to the process of joining multiple strings together.</li>
  <li>Type casting and concatenation are valuable for preventing type conflicts and formatting output.</li>
</ul>

~~~
# Type conversion example
x = "10"
y = int(x)  # Convert x from string to integer

# String concatenation example
first_name = "John"
last_name = "Doe"
full_name = first_name + " " + last_name

# Type casting and concatenation example
num = 10
text = "The number is: " + str(num)  # Convert num to string for concatenation
print(text)
~~~~


### List

<ul>
  <li>Lists are groupings of various types of variables or values.</li>
  <li>The elements in a list are ordered, can be modified, and allow duplicate values.</li>
  <li>Lists can include sublists as elements, creating lists with multiple levels of nesting which are also called multidimensional lists.</li>
</ul>

~~~
# List example
my_list = [1, "apple", True, 3.14]

# List properties example
my_list = [1, 2, 3, 4, 1, 2]

# Multidimensional list example
multidimensional_list = [[1, 2, 3], ["a", "b", "c"], [True, False]]
~~~

<br>

<p><b>Helpful operations for lists:</b></p>

<ol type="1">
  <li><b>list.append(element):</b> Add an item to the end of a list</li>
  <li><b>list.pop(i):</b> Remove and retrieve the (i + 1)th element from the list</li>
  <li><b>print(list[i]): </b> Print the (i + 1)th element of the list</li>
  <li><b>len(list): </b> Determine the length of a list</li>
  <li><b>element in list: </b> Check if an element is present in the list; returns True if found, False otherwise</li>
  <li><b>list.reverse(): </b> Print the list in reverse order </li>
  <li><b>list.sort(): </b> Arrange the list elements in ascending order</li>
</ol>

> **_NOTE:_** In Python, list indexing starts from 0

 ~~~
# List functions demonstration
my_list = [1, 2, 3]

# list.append() example
my_list.append(4)

# list.pop() example
popped_item = my_list.pop(1)

# Print list element example
print(my_list[0])

# len() example
list_length = len(my_list)

# Check if element is in list example
is_present = 4 in my_list

# list.reverse() example
my_list.reverse()

# list.sort() example
my_list.sort()
  ~~~

<br>

<p><b>Slicing allows extracting a portion of a list or string for display.</b></p>
<ul>
  <li>To perform slicing, use the colon notation inside square brackets following the list name.</li>
  <li>The slicing syntax appears as follows: <b>list[start:stop:step].</b></li>
  <li>Practice: Given the list numbers = [99, 20, 56, 10, 5], arrange it in ascending order.</li>
</ul>

~~~
# Slicing example with a list
numbers = [1, 2, 3, 4, 5]
sliced_numbers = numbers[1:4]
print(sliced_numbers)  # Output: [2, 3, 4]

# Slicing syntax example
numbers = [1, 2, 3, 4, 5]
sliced_numbers = numbers[1:4]

# Slicing syntax explanation
numbers = [1, 2, 3, 4, 5]
sliced_numbers = numbers[1:4:2]

# Sorting a list exercise
numbers = [99, 20, 56, 10, 5]
numbers.sort()
print(numbers)  # Output: [5, 10, 20, 56, 99]
~~~

### Dictionaries

<p><b>Dictionaries are collections that store key:value pairs.</b></p>

<ul>
  <li>Dictionaries are structured collections that maintain order, support modification, and do not permit duplicate keys.</li>
  <li>Unlike lists, dictionary elements are identified by their keys rather than numerical indices.</li>
  <li>Accessing dictionary elements resembles accessing list elements, but you use square brackets with the key instead of an index <b>(dictionary[key]).</b></li>
</ul>

~~~
# Dictionary example
my_dict = {"name": "John", "age": 30, "city": "New York"}

# Dictionary properties example
my_dict = {"name": "John", "age": 30, "city": "New York"}

# Accessing dictionary elements example
print(my_dict["name"])

# Accessing dictionary elements example
print(my_dict["age"])
~~~
<br>

<p><b>Useful dictionaries functions (rather similar to lists):</b></p>
<ol type="*">
  <li><b>print(dictionary(key]):</b> Display the value associated with a specific key</li>
  <li><b>dictionary.pop(key):</b> Eliminate and retrieve the value associated with a given key</li>
  <li><b>len(dictionary):</b> Determine the number of key-value pairs in a dictionary or It means that the length of a dictionary.</li>
  <li><b>key in dictionary:</b> Check if a key exists in the dictionary; returns True if found, False otherwise.</li>
</ol>

~~~
# Dictionary functions demonstration
my_dict = {"name": "John", "age": 30, "city": "New York"}

# print(dictionary[key]) example
print(my_dict["name"])

# dictionary.pop(key) example
removed_value = my_dict.pop("age")

# len(dictionary) example
dict_length = len(my_dict)

# key in dictionary example
is_present = "name" in my_dict
~~~

### Sets and Tuples

<ul>
  <li>Sets are unordered, unchangeable and unable to be modified or indexed. Nevertheless, elements can be added to or removed from sets.</li>
  <li>Tuples are ordered collections of elements that are immutable; neither can elements be modified by index nor new elements be added to a tuple.</li>
</ul>

~~~
# Set example
my_set = {1, 2, 3}

# Tuple example
my_tuple = (1, 2, 3)
~~~
<br>
<p>After being converted to a variable of type set, notice that the list_set no longer contains any repeating elements.</p>

~~~
# Original list with duplicate elements
original_list = [1, 2, 3, 1, 2, 4, 5]

# Convert the list to a set
list_set = set(original_list)

# Display the original list and the set
print("Original list:", original_list)
print("Set without duplicates:", list_set)
~~~
___

~~~
Original list: [1, 2, 3, 1, 2, 4, 5]
Set without duplicates: {1, 2, 3, 4, 5}
~~~

>  **_NOTE:_** When we want to move around items that we do not wish to change, we can utilize tuples.

### Loops and Branching

<ul>
  <li>Branching directs code execution paths according to the evaluation of one or more conditions.</li>
  <li>Branching employs if statements, which can incorporate elif and else statements. This structure dictates: 'If condition_1 is met, execute action_1; otherwise, if condition_2 is met, execute action_2; if neither condition holds, execute action_3'.</li>
  <li>An if statement can combine multiple conditions using the 'and' and 'or' operators</li>
  <li>Nested if statements, where one if statement is contained within another, execute only if both conditions are met.</li>
  <li>If statements utilize comparisons and Booleans. Conditions determining branching paths rely on comparison operators, yielding Boolean outcomes.</li>
  <li>Python employs comparison operators such as '==', '>=', and '<='.</li>
  <li>Booleans denote either True or False. Variables holding Boolean values are assigned either True or False.</li>
</ul>

~~~
# Branching example
x = 10
if x > 5:
    print("x is greater than 5")

# If-elif-else example
x = 10
if x > 15:
    print("x is greater than 15")
elif x > 5:
    print("x is greater than 5 but less than or equal to 15")
else:
    print("x is less than or equal to 5")

# Combining conditions example
x = 10
if x > 5 and x < 15:
    print("x is between 5 and 15")

# Nested if example
x = 10
if x > 5:
    if x < 15:
        print("x is between 5 and 15")

# Boolean conditions example
x = 10
y = 20
if x == 10 and y >= 15:
    print("Both conditions are met")

# Boolean variables example
is_raining = False
has_umbrella = True
if is_raining and has_umbrella:
    print("Bring your umbrella!")
~~~

<br>

<ul>
  <li>Loops repeat a set of instructions for a specified number of times.</li>
  <li>There are two main types of loops: while loops and for loops.</li>
  <li>While loops execute instructions repeatedly as long as a specified condition remains true. It's called a 'loop' because the code block is iterated until the condition becomes false.</li>
  <li>For loops execute instructions for a predetermined number of iterations, acting as iterators to traverse the items of a sequence or any iterable object.</li>
  <li>Loops are utilized to iterate through collections like lists and dictionaries.</li>
</ul>

~~~
# Loop example
for i in range(5):
    print("Iteration:", i)

# While loop example
x = 0
while x < 5:
    print("x is less than 5")
    x += 1

# While loop example
x = 0
while x < 5:
    print("x is less than 5")
    x += 1

# For loop example
for i in range(5):
    print("Iteration:", i)

# Iterating over a list example
my_list = [1, 2, 3, 4, 5]
for item in my_list:
    print("Item:", item)
~~~
<br>

<ul>
  <li>Before proceeding to for loops, let's discuss ranges.</li>
  <li>The range() function generates a sequence starting from 0 and ending before a specified number.</li>
  <li>Typically, the range function is expressed as: range(start, stop, step).</li>
  <li>By default, ranges commence at 0 and increment by 1.</li>
</ul>

~~~
# Range example
for i in range(5):
    print("Iteration:", i)

# Range function example
for i in range(5):
    print("Iteration:", i)

# Range function with custom start, stop, and step
for i in range(1, 10, 2):
    print("Iteration:", i)

# Default range behavior example
for i in range(5):
    print("Iteration:", i)
~~~
<br>

<p>Using a for loop:</p>

~~~
# Using a for loop
total_sum = 0
for i in range(1, 101):
    total_sum += i
print("Sum using for loop:", total_sum)
~~~

<br>
<p>Using the Gauss Sum formula:</p>

~~~
# Using Gauss Sum formula
n = 100
gauss_sum = n * (n + 1) // 2
print("Sum using Gauss Sum formula:", gauss_sum)
~~~


## Usage & Contributing

You can clone the repository and download your local to work on it. If you want to provide more examples or if you detected any mistake on the example, please, review and correct then notify me with a commit request.

## License 🪪

TUM - Technical University of Munich

## Resources

<p><b>Books:</b></p>
<ul>
    <li>Model Building in Mathematical Programming 5th Edition by H. Paul Williams</li>
    <li>Planning and Scheduling in Manufacturing and Services By Michael L. Pinedo </li>
</ul>

