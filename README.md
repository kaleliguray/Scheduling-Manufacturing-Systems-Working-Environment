
![Image]('/Users/giraykaleli/Desktop/Screen Shot 2025-01-29 at 00.06.14 AM.png')

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
  - [Chapter 1](#chapter-1) 
    - [String, Print, Type And Comment](#string-print-type-and-comment)
    - [Integers and Floats](#integers-and-floats)
    - [Variable Assignment And Mathematical Operations](#variable-assignment-and-mathematical-operations)
    - [Type Casting And Concatenation](#type-casting-and-concatenation)
    - [List](#list)
    - [Dictionaries](#dictionaries)
    - [Sets and Tuples](#sets-and-tuples)
    - [Loops and Branching](#loops-and-branching)
  - [Chapter 2](#chapter-2)
    - [Functions and Packages](#functions-and-packages)
      - [Function Definition](#function-definition)
      - [Function Arguments and Default Values](#function-arguments-and-default-values)
      - [NumPy](#numpy)
      - [Pandas](#pandas)
  - [Chapter 3](#chapter-3)
    - [Introduction to Gurobi](#introduction-to-gurobi)
    - [Installation](#installation)
    - [Simple Gurobi Example](#simple-gurobi-example)
    - [Data Preparation and Further Gurobi Examples in PyCharm](#data-preparation-and-further-gurobi-examples-in-pycharm)
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

### Chapter 1

#### String, Print, Type And Comment

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

#### Integers And Floats

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

#### Variable Assignment And Mathematical Operations

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


#### Type Casting And Concatenation

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


#### List

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

#### Dictionaries

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

#### Sets and Tuples

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

#### Loops and Branching

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

### Chapter 2

#### Functions and Packages

##### Function Definition

<ul>
  <li>Functions are sections of code that are executed only when they are specifically requested or called.</li>
  <li>Benefits of functions:</li>
  <ul>
    <li>Enhance code clarity and comprehension.</li>
    <li>Enable code reusability within the same script or across various programs.</li>
  </ul>
</ul>

~~~
# Define a simple function
def greet():
    print("Hello, world!")

# Call the function to execute its code block
greet()

# Functions enhance code readability and can be reused multiple times
# For example:
greet()  # This call executes the greet function again
~~~
___
~~~
Hello, world!
~~~

> **_NOTE_** The advantages of readability and code reuse.

##### Function Arguments and Default Values

<ul>
  <li>In the previous example, the function didn't require any input. However, in certain situations, functions need input information, which we call arguments.</li>
  <li>Arguments are specified within the parentheses after the function name and are separated by commas.</li>
  <li>Arguments can have values of various types, but it's crucial to provide the correct types when calling functions.</li>
  <li>When calling functions, arguments are provided within the parentheses in the format <b>argument_Name = argument_Value</b>. Alternatively, only values can be specified in the parentheses, but in that case, the arguments must be in the same order as defined in the function.</li>
</ul>

~~~
# Define a function with input arguments
def greet(name, age):
    print(f"Hello, {name}! You are {age} years old.")

# Call the function with arguments specified by name
greet(name="Alice", age=30)

# Call the function with arguments specified by position
greet("Bob", 25)
~~~
___
~~~
Hello, Alice! You are 30 years old.
Hello, Bob! You are 25 years old.
~~~

> **_NOTE_** Providing arguments by name enhances code readability and reduces the risk of errors when calling functions.

<ul>
  <li>Functions can include arguments with default values, which may or may not be provided when calling the function.</li>
  <li>Arguments with default values must be placed at the end of the parameter list.</li>
</ul>

~~~
# Define a function with an argument having a default value
def greet(name, message="Hello"):
    print(f"{message}, {name}!")

# Call the function without specifying the optional argument
greet("Alice")

# Call the function and specify the optional argument
greet("Bob", "Hi")
~~~
___
~~~
Hello, Alice!
Hi, Bob!
~~~

> **_NOTE_** This demonstrates how functions can have arguments with default values, providing flexibility when calling the function.

<ul>
  <li>Variables created and utilized within a function (local variables) cannot be accessed outside of that function.</li>
  <li>Variables defined in the main program (outside of any function) can be accessed within a function using the keyword <b>global</b> (although it's not strictly necessary, using <b>global</b> makes it clearer that the variable is being accessed from outside the function).</li>
</ul>

~~~
# Define a global variable
global_var = "I'm a global variable"

# Define a function that uses a global variable
def func():
    # Access the global variable inside the function
    print("Inside the function:", global_var)

# Call the function
func()

# Trying to access the local variable outside the function will result in an error
# Uncommenting the line below will raise a NameError
# print("Outside the function:", local_var)
~~~
___
~~~
Inside the function: I'm a global variable
~~~

> **_NOTE_** Attempting to access a local variable defined within the function outside of it will result in an error, as local variables are not visible outside of their defining scope.

##### NumPy

<ul>
  <li>NumPy is a Python library designed for array manipulation, linear algebra operations, Fourier transforms, and matrix computations.</li>
  <li>NumPy is particularly valuable because its array objects are more efficient than native Python lists.</li>
  <li>To utilize NumPy, it must first be installed. In integrated development environments (IDEs), installation is typically achieved by executing the command pip install numpy in the terminal. Subsequently, it must be imported into the .py file using the import numpy command. Note: In Google Colab, NumPy is pre-installed, so only importing is necessary.</li>
  <li>Python allows us to import libraries using aliases, enabling the use of the library in the script without typing its full name every time. For NumPy, the commonly used alias is np.</li>
</ul>

~~~
# Importing NumPy with the np alias
import numpy as np

# Creating a NumPy array
arr = np.array([1, 2, 3, 4, 5])

# Printing the array
print(arr)
~~~
___
~~~
[1 2 3 4 5]
~~~

> **_NOTE_** NumPy is imported using the alias np. Then, a NumPy array is created and printed. Using the alias np allows us to reference NumPy functions and objects more concisely throughout the script.

<ul>
  <li>The NumPy library's array object is known as ndarray. Arrays can be generated using the array function provided by the NumPy package.</li>
  <li>NumPy arrays can have various dimensions. A 0-D array represents a scalar value, a 1-D array represents a vector, a 2-D array represents a matrix, a 3-D array represents a collection of 2-D arrays, and so on. The dimensionality of an array can be determined using the ndim attribute of the array.</li>
</ul>

~~~
import numpy as np

# Creating different-dimensional NumPy arrays
scalar_arr = np.array(5)  # 0-D array (scalar)
vector_arr = np.array([1, 2, 3])  # 1-D array (vector)
matrix_arr = np.array([[1, 2, 3], [4, 5, 6]])  # 2-D array (matrix)
collection_arr = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])  # 3-D array (collection of 2-D arrays)

# Checking the dimensions of the arrays
print("Dimension of scalar_arr:", scalar_arr.ndim)
print("Dimension of vector_arr:", vector_arr.ndim)
print("Dimension of matrix_arr:", matrix_arr.ndim)
print("Dimension of collection_arr:", collection_arr.ndim)
~~~
___
~~~
Dimension of scalar_arr: 0
Dimension of vector_arr: 1
Dimension of matrix_arr: 2
Dimension of collection_arr: 3
~~~

> **_NOTE_** Various NumPy arrays of different dimensions are created using the array function. Then, the dimensionality of each array is determined using the ndim attribute and printed. This demonstrates how NumPy arrays can represent scalars, vectors, matrices, and higher-dimensional structures.

<ul>
  <li>In NumPy ndarrays, indexing begins at 0, similar to lists. Slicing operations function in the same manner.</li>
  <li>Ndarrays offer a valuable attribute called shape, which provides the count of elements along each dimension. The shape attribute returns a tuple where each element represents the number of elements in the respective dimension.</li>
  <li>Ndarrays can be reshaped using the reshape() function by specifying the desired shape as an argument.</li>
</ul>

~~~
import numpy as np

# Creating a NumPy array
arr = np.array([[1, 2, 3], [4, 5, 6]])

# Accessing elements using indexing and slicing
print("Element at index (0, 1):", arr[0, 1])  # Output: 2
print("First row:", arr[0, :])  # Output: [1 2 3]
print("Last column:", arr[:, -1])  # Output: [3 6]

# Checking the shape of the array
print("Shape of the array:", arr.shape)  # Output: (2, 3)

# Reshaping the array
reshaped_arr = arr.reshape(3, 2)
print("Reshaped array:")
print(reshaped_arr)
~~~
___
~~~
Element at index (0, 1): 2
First row: [1 2 3]
Last column: [3 6]
Shape of the array: (2, 3)
Reshaped array:
[[1 2]
 [3 4]
 [5 6]]
Element at index (0, 1): 2
First row: [1 2 3]
Last column: [3 6]
Shape of the array: (2, 3)
Reshaped array:
[[1 2]
 [3 4]
 [5 6]]
~~~

> **_NOTE_** a NumPy array is created and accessed using indexing and slicing operations. The shape attribute is then used to determine the dimensions of the array. Finally, the array is reshaped using the reshape() function to convert it from a 2x3 array to a 3x2 array.

<ul>
  <li>Lists and ndarrays exhibit differences in how mathematical operations are performed on them.</li>
  <li>1-D arrays are treated as vectors, and mathematical operations are applied element-wise.</li>
  <li>A comparison between 1-D lists and arrays is presented below.</li>
</ul>

~~~
import numpy as np

# Define a 1-D list and a 1-D array
list_1d = [1, 2, 3, 4, 5]
array_1d = np.array([1, 2, 3, 4, 5])

# Perform a mathematical operation (multiplication) on the list and the array
list_result = [x * 2 for x in list_1d]
array_result = array_1d * 2

# Print the results
print("Result of multiplying the list by 2:", list_result)
print("Result of multiplying the array by 2:", array_result)
~~~
___
~~~
Result of multiplying the list by 2: [2, 4, 6, 8, 10]
Result of multiplying the array by 2: [ 2  4  6  8 10]
~~~

> **_NOTE_** A 1-D list (list_1d) and a 1-D array (array_1d) are defined. Then, a mathematical operation (multiplication by 2) is performed on both the list and the array. The results are printed, illustrating how the mathematical operation is applied differently to the list (element-wise multiplication) and the array (each element is multiplied by 2).

<ul>
  <li>Operations such as logarithm, square root, and exponentiation can be applied to ndarrays in a similar manner, without the need to iterate through all the elements of the array.</li>
</ul>

~~~
import numpy as np

# Create a NumPy array
arr = np.array([1, 4, 9, 16, 25])

# Apply logarithm, square root, and exponentiation operations to the array
log_arr = np.log(arr)
sqrt_arr = np.sqrt(arr)
exp_arr = np.exp(arr)

# Print the results
print("Logarithm of the array:", log_arr)
print("Square root of the array:", sqrt_arr)
print("Exponential of the array:", exp_arr)
~~~
___
~~~
Logarithm of the array: [0.         1.38629436 2.19722458 2.77258872 3.21887582]
Square root of the array: [1. 2. 3. 4. 5.]
Exponential of the array: [2.71828183e+00 5.45981500e+01 8.10308393e+03 8.88611052e+06
 7.20048993e+10]
~~~

> **_NOTE_** A NumPy array arr containing square numbers is created. Then, logarithm, square root, and exponentiation operations are applied to the array using NumPy functions np.log(), np.sqrt(), and np.exp() respectively. The results are printed, demonstrating how these operations can be directly applied to ndarrays without the need for explicit iteration.

<ul>
  <li>The operations explained for 1-D arrays function similarly when applied to arrays with higher dimensions.</li>
  <li>Below are a few examples involving matrices.</li>
  <li>Important ndarray functions:</li>
  <ol tyep="1">
    <li><b>np.dot(array_1, array_2): </b> Computes the dot product between two arrays.</li>
    <li><b>array_1 * array_2:  </b> Returns an array where each element of the first array is multiplied with the corresponding element of the second array.</li>
    <li><b>array.T:  </b>  Returns the transpose of the array.</li>
    <li><b>np.matmul(array_1, array_2):  </b> Computes the matrix product of two arrays.</li>
  </ol>
  <li><b>Note: </b> 2-D arrays can be indexed similarly to lists (array[i][j]). However, they can also be indexed as array[i, j]. This indexing method applies to higher-dimensional arrays as well.</li>
</ul>

~~~
import numpy as np

# Create two 2-D arrays
array_1 = np.array([[1, 2], [3, 4]])
array_2 = np.array([[5, 6], [7, 8]])

# Compute the dot product of the arrays
dot_product = np.dot(array_1, array_2)

# Element-wise multiplication of the arrays
element_wise_product = array_1 * array_2

# Transpose of array_1
transposed_array_1 = array_1.T

# Matrix multiplication of the arrays
matrix_product = np.matmul(array_1, array_2)

# Print the results
print("Dot product of the arrays:")
print(dot_product)
print("\nElement-wise product of the arrays:")
print(element_wise_product)
print("\nTranspose of array_1:")
print(transposed_array_1)
print("\nMatrix product of the arrays:")
print(matrix_product)
~~~
___
~~~
Dot product of the arrays:
[[19 22]
 [43 50]]

Element-wise product of the arrays:
[[ 5 12]
 [21 32]]

Transpose of array_1:
[[1 3]
 [2 4]]

Matrix product of the arrays:
[[19 22]
 [43 50]]
~~~

> **_NOTE_** two 2-D arrays array_1 and array_2 are created. The dot product, element-wise product, transpose of array_1, and matrix product of the arrays are computed using the provided NumPy functions. The results showcase the application of these functions on arrays of higher dimensions.

<ul>
  <li>NumPy provides functions to generate arrays filled with zeros or ones using <b>np.zeros(shape)</b> and <b>np.ones(shape)</b> respectively.</li>
</ul>

~~~
import numpy as np

# Create a 2x3 array filled with zeros
zeros_array = np.zeros((2, 3))

# Create a 3x2 array filled with ones
ones_array = np.ones((3, 2))

# Print the arrays
print("Zeros array:")
print(zeros_array)
print("\nOnes array:")
print(ones_array)
~~~
___
~~~
Zeros array:
[[0. 0. 0.]
 [0. 0. 0.]]

Ones array:
[[1. 1.]
 [1. 1.]
 [1. 1.]]
~~~

> **_NOTE_** The np.zeros() and np.ones() functions are used to create arrays filled with zeros and ones respectively. The shape of the arrays is specified as a tuple argument. Finally, the arrays are printed to showcase their content.

<ul>
  <li>NumPy includes a module named Random, which facilitates working with random numbers and data distributions.</li>
  <li>This module is particularly valuable for generating data.</li>
  <li>Key functions from the Random module:</li>
  <ol>
    <li><b>random.randint(upper_limit): </b> Generates a random integer between 0 and the specified upper limit.</li>
    <li><b>random.rand(): </b> Generates a random float between 0 and 1.</li>
    <li><b>random.choice(array): </b> Selects a value randomly from the provided 1-D array.</li>
  </ol>
  <li><b>Note: </b> These functions can also accept an argument specifying the size of the array to be returned.</li>
</ul>

~~~
import numpy as np

# Generate a random integer between 0 and 9
random_int = np.random.randint(10)
print("Random integer between 0 and 9:", random_int)

# Generate a random float between 0 and 1
random_float = np.random.rand()
print("Random float between 0 and 1:", random_float)

# Generate a random choice from a provided 1-D array
array = np.array([1, 2, 3, 4, 5])
random_choice = np.random.choice(array)
print("Random choice from the array:", random_choice)
~~~
___
~~~
Random integer between 0 and 9: 0
Random float between 0 and 1: 0.8258953159664709
Random choice from the array: 1
~~~

> **_NOTE_** The functions np.random.randint(), np.random.rand(), and np.random.choice() from the NumPy Random module are demonstrated. Each function generates random numbers or selects random values from an array, showcasing their utility for generating random data.

##### Pandas

<ul>
  <li>Pandas is a Python library used for handling datasets.</li>
  <li>It offers essential functions for analyzing, cleaning, exploring, manipulating, and <b>visualizing</b> data.</li>
  <li>Given that optimization problems often involve large datasets, Pandas is highly relevant for this course.</li>
</ul>

~~~
import pandas as pd

# Create a sample DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie', 'David'],
        'Age': [25, 30, 35, 40],
        'Salary': [50000, 60000, 70000, 80000]}
df = pd.DataFrame(data)

# Print the DataFrame
print("Sample DataFrame:")
print(df)
~~~
___
~~~
Sample DataFrame:
      Name  Age  Salary
0    Alice   25   50000
1      Bob   30   60000
2  Charlie   35   70000
3    David   40   80000
~~~

> **_NOTE_** Pandas is used to create a sample DataFrame named df containing information about individuals. The DataFrame is then printed to showcase how Pandas can be used to handle and analyze tabular data.
> **_NOTE_** This result displays the created DataFrame containing information about individuals, such as their names, ages, and salaries. It demonstrates how Pandas can be used to handle and analyze tabular data effectively.

<ul>
  <li>To install Pandas, use the command <b>pip install pandas</b> in the terminal. Then, import it into the .py file using <b>import pandas.</b> Note: In Google Colab, Pandas is pre-installed, so only importing is necessary.</li>
  <li>Pandas utilizes Series to represent the columns of a table. Series can be formed from either a one-dimensional list or key-value pairs. They are created using the <b>pd.Series(list or dict)</b> function. The <b>index</b> argument in <b>pd.Series()</b> specifies the row labels, with the length of the index list matching the number of rows in the provided columns.</li>
</ul>

~~~
import pandas as pd

# Create a Series from a one-dimensional list
list_series = pd.Series([10, 20, 30, 40])

# Create a Series from key-value pairs
dict_series = pd.Series({'A': 100, 'B': 200, 'C': 300, 'D': 400})

# Print the Series
print("Series created from a one-dimensional list:")
print(list_series)
print("\nSeries created from key-value pairs:")
print(dict_series)
~~~
___
~~~
Series created from a one-dimensional list:
0    10
1    20
2    30
3    40
dtype: int64

Series created from key-value pairs:
A    100
B    200
C    300
D    400
dtype: int64
~~~

> **_NOTE_** Pandas Series are created using both a one-dimensional list and key-value pairs. The resulting Series are then printed to demonstrate how Series can be created and represented in Pandas.
> **_NOTE_** This result displays the Series created from both a one-dimensional list and key-value pairs. It showcases the structure of Series in Pandas, where index labels are automatically assigned to the elements.

<ul>
  <li>When creating Series from dictionaries (key/value pairs), the index argument is unnecessary since the dictionary keys already serve as labels.</li>
  <li>Dataframes in Pandas represent tables with rows and columns. They are constructed using the <b>pd.DataFrame()</b> function. This function also includes an index attribute for assigning row labels.</li>
</ul>

~~~
import pandas as pd

# Create a Series from key-value pairs without specifying the index
dict_series = pd.Series({'A': 100, 'B': 200, 'C': 300, 'D': 400})

# Create a DataFrame from a dictionary of lists
data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Age': [25, 30, 35],
        'Salary': [50000, 60000, 70000]}
df = pd.DataFrame(data)

# Print the Series and DataFrame
print("Series created from key-value pairs (dictionary):")
print(dict_series)
print("\nDataFrame created from a dictionary of lists:")
print(df)
~~~
___
~~~
Series created from key-value pairs (dictionary):
A    100
B    200
C    300
D    400
dtype: int64

DataFrame created from a dictionary of lists:
      Name  Age  Salary
0    Alice   25   50000
1      Bob   30   60000
2  Charlie   35   70000
~~~

> **_NOTE_** A Series is created from key-value pairs without specifying the index since the keys already serve as labels. Additionally, a DataFrame is created from a dictionary of lists using the pd.DataFrame() function. The resulting Series and DataFrame are then printed to showcase their structure and content.

> **_NOTE_** This result displays the Series created from key-value pairs (dictionary) and the DataFrame created from a dictionary of lists. It illustrates the structure and content of both Series and DataFrames in Pandas.

<ul>
  <li>DataFrame rows can be accessed using the <b>data_Frame.loc[row_Index]</b> attribute. If row labels are used, the row name can alternatively be utilized instead of the index.</li>
  <li>DataFrame columns can be accessed by specifying the column name within square brackets or by passing a list of column names if multiple columns are required <b>(e.g., data_Frame[["col_1", "col_2"]]).</b></li>
</ul>

~~~
import pandas as pd

# Create a DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Age': [25, 30, 35],
        'Salary': [50000, 60000, 70000]}
df = pd.DataFrame(data)

# Access a specific row by index
row_index_1 = df.loc[1]
print("Accessing row by index:")
print(row_index_1)

# Access a specific row by label
row_label_Alice = df.loc['Alice']
print("\nAccessing row by label:")
print(row_label_Alice)

# Access a specific column
column_age = df['Age']
print("\nAccessing a specific column:")
print(column_age)

# Accessing multiple columns
columns_name_salary = df[['Name', 'Salary']]
print("\nAccessing multiple columns:")
print(columns_name_salary)
~~~
___
~~~
Accessing row by index:
Name      Bob
Age        30
Salary  60000
Name: 1, dtype: object

Accessing row by label:
Name      Alice
Age          25
Salary    50000
Name: Alice, dtype: object

Accessing a specific column:
0    25
1    30
2    35
Name: Age, dtype: int64

Accessing multiple columns:
      Name  Salary
0    Alice   50000
1      Bob   60000
2  Charlie   70000
~~~

> **_NOTE_** A DataFrame is created using a dictionary. It then demonstrates accessing specific rows by both index and label, accessing a single column, and accessing multiple columns. Each operation showcases different methods of accessing rows and columns in a DataFrame.
> **_NOTE_** This result demonstrates accessing specific rows and columns in a DataFrame. It includes accessing rows by both index and label, accessing a single column, and accessing multiple columns. Each operation showcases different methods of accessing data in a DataFrame using Pandas.

<ul>
  <li>Rows in a DataFrame can be filtered based on column values using comparison operators.</li>
  <li>By accessing the first element of the shape attribute of the filtered DataFrame, you can determine the number of rows that meet the specified condition.</li>
</ul>

~~~
import pandas as pd

# Create a DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie', 'David'],
        'Age': [25, 30, 35, 40],
        'Salary': [50000, 60000, 70000, 80000]}
df = pd.DataFrame(data)

# Filter rows where Age is greater than 30
filtered_df = df[df['Age'] > 30]

# Get the number of rows that satisfy the condition
num_rows_satisfy_condition = filtered_df.shape[0]

# Print the filtered DataFrame and the number of rows
print("Filtered DataFrame:")
print(filtered_df)
print("\nNumber of rows where Age is greater than 30:", num_rows_satisfy_condition)
~~~
___
~~~
Filtered DataFrame:
      Name  Age  Salary
2  Charlie   35   70000
3    David   40   80000

Number of rows where Age is greater than 30: 2
~~~

> **_NOTE_** a DataFrame is created, and then rows are filtered based on the condition where the Age column is greater than 30. The filtered DataFrame and the number of rows that satisfy the condition are then printed. This demonstrates how to filter rows in a DataFrame based on column values using Pandas.

<ul>
  <li>ou can import datasets using the <b>pandas.read_csv()</b> function.</li>
</ul>

~~~
import pandas as pd

# Import a CSV file as a DataFrame
df = pd.read_csv('example.csv')

# Print the DataFrame
print("Imported DataFrame:")
print(df)
~~~
___
~~~
Imported DataFrame:
   Column1  Column2  Column3
0        1        4        7
1        2        5        8
2        3        6        9
~~~

> **_NOTE_** A CSV file named 'example.csv' is imported as a DataFrame using the pd.read_csv() function. The resulting DataFrame is then printed to display the imported dataset. This demonstrates how to import datasets from CSV files using Pandas.

<ul>
  <li>You can use the head(n) and tail(n) functions to display the first and last n rows of a DataFrame. If no argument is provided, 5 rows will be shown by default.</li>
</ul>

~~~
import pandas as pd

# Create a DataFrame
data = {'Column1': [1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
        'Column2': ['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J']}
df = pd.DataFrame(data)

# Display the first 3 rows using head(n)
print("First 3 rows:")
print(df.head(3))

# Display the last 3 rows using tail(n)
print("\nLast 3 rows:")
print(df.tail(3))
~~~
___
~~~
First 3 rows:
   Column1 Column2
0        1       A
1        2       B
2        3       C

Last 3 rows:
   Column1 Column2
7        8       H
8        9       I
9       10       J
~~~

> **_NOTE_** a DataFrame is created, and then the first 3 rows and last 3 rows are displayed using the head(n) and tail(n) functions, respectively. This demonstrates how to view specific rows of a DataFrame using Pandas.

## Chapter 3

<p><a href="https://github.com/kaleliguray/Scheduling-Manufacturing-Systems-Working-Environment/tree/main/lecture_3">In the Lecture 3 folder,</a> you'll find detailed explanations, coding examples, and output.</p>

> **_NOTE_** During the lecture period, this Python Lecture which I have benefited was created by Daniel Postica and Mirko Schömig 
    <ul>
      <li><a href="https://www.ot.mgt.tum.de/scm/home/">Chair of Production and Supply Chain Management (Grunow)</a></li>
      <li>School of Management, Technical University of Munich</li>
    </ul>

### Introduction to Gurobi

<div>
  <ul>
  <li>Download Python at: https://www.python.org/downloads/</li>
  <li>Download PyCharm at: https://www.jetbrains.com/pycharm/download (Scroll down for community edition)</li>
  <li>Create an account at: https://www.gurobi.com</li>
  <li>After creating the account go to: https://www.gurobi.com/academia/academic-program-and-licenses/ and select Academic Named-User License.</li>
  <li>On the next page the installation instructions are displayed.</li>
</ul>
</div>

![Screen Shot 2024-05-06 at 21 50 37 PM](https://github.com/kaleliguray/Scheduling-Manufacturing-Systems-Working-Environment/assets/55591718/8ce8ee8e-fb65-4141-bc42-0ab50c390c29)

### Simple Gurobi Example

<p><a href="https://github.com/kaleliguray/Scheduling-Manufacturing-Systems-Working-Environment/blob/main/lecture_3/Lecture_3_Code_Along.ipynb">Please visit the lecture 3 folder!</a></p>

### Data Preparation and Further Gurobi Examples in PyCharm

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

