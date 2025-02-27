# Functions in Python
Python Functions is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.

Some Benefits of Using Functions
1) Increase Code Readability 
2) Increase Code Reusability

## Types of Functions in Python
1) Built-in/ Base Python Function - print("Hello")
                                    len("Welcome")
2) Custom defined function -
        # defining a function
         def greet():
           print("Hello World!")
         # calling the function
           greet()

## Built-in Functins
### 1) Type Conversion Functions
These functions convert one data type into another.
int("10")                      #converts string to integer -> 10
float (3.14)                   #converts string to float -> 3.14
str(100)                       #converts integer to string -> '100'
bool(0)                        #converts to boolean (False)
list("abc")                    #converts string to list-> ['a', 'b', 'c']
tuple([1 ,2 ,3])               #converts list to tuple ->(1, 2, 3)
set[(1 ,2 ,3)]                 #converts list to set ->{1, 2}
dict ([(1,"one"),(2,"two")])   #converts list of tuples to dictionary

### 2) Input and Output Functions

year=int(input("enter the birth year: "))
print("age",2025-year)

Output:
enter the birth year:  2010
age 15


### 3) Mathematical Functions
These functions perform mathematical operations.

abs(-5)       # Returns absolute value = 5
pow(2,3)      # 2^3 = 8
round(3,7)    # Rounds to nearest integer = 4
divmod(10,3)  # Returns quotient and remainder -> ( 3,1)

### 4) Iterables and Sequences Functions
Used for working with lists, tuples and ranges 

len([1,2,3])    ->  3
max(4,7,2)      ->  7
min([10,20,30]) -> 10
sum([1,2,3])    -> 6
sorted([3,1,2]) -> [1, 2, 3]
range(5)        -> range(0, 5)

### 5) Object and Memory Functions
Used for object manipulation.

type(10)               #Returns type -> int
id(10)                 #Returns memory address
isinstance(10, int)    #Checks if object is of a type -> True

### 6) File Handling Functions
Used for working with files.
open("files.txt", "r")   # opens file in read mode

example: 
with open("C:\\Users\\nafna\\OneDrive\\Documents\\data science and analytics.txt", "r") as f:
  data = f.readlines()[0]
print(data)

with open("sample.txt", "w") as f: 
    f.write("Hello World!") 
    
example:
with open("C:\\Users\\nafna\\OneDrive\\Documents\\hello world!.txt", "w") as f:
    f.write("Hello world")    
    
### 7) Miscellaneous Functions
1. len() - Get the length of an object
This function returns the length (the number of items) of an object like a string, list, tuple, etc.
Example:


len([5,10,15])


Output: 3

2. type() - Get the type of an object

type(10)

3. range() - Generate a sequence of numbers
This function is typically used in loops to generate a sequence of numbers.
list(range(5))   ->  [0, 1, 2, 3, 4]
tuple(range(5))  ->  (0, 1, 2, 3, 4)

   
## Custom Functions

### 1.  Defining Functions


def greet():
    print("Hello World!")
greet()

### 2.  Defining and Calling Functions 
![Screenshot 2025-02-27 172013](https://github.com/user-attachments/assets/76e49892-21ce-46fe-90ac-8b3e0b4d6663)

![Screenshot 2025-02-27 172028](https://github.com/user-attachments/assets/7f1f9698-1b09-4a4c-94e3-c2428917ae22)

* Use def function_name(): to define a function.
* Call a function function_name().



def add_numbers():
    a=10
    b=20
    print("Sum:",a+b)
add_numbers()


Sum: 30

### 3. Function Arguments
Functions can take parameters to perform operations on inputs.

1) Example (Positional Arguments):

def add(a,b):
    print("Sum:",a+b)
add(5,3)


Sum: 10

2) Example (Keyword Arguments & Default Arguments):

3) 
def greet(name="Guest"):
    print(f"Hello, {name}!")
greet()  #Uses default value
greet("Alice")  #Uses provided argument


Output: 

Hello, Guest!

Hello, Alice!


### 4. Return Statement
A function can return a value using the keyword



def add(a,b):
    return a+b
result = add(4,6)
print("Result:",result)



Output: 
Result: 10

### 5. Function with Multiple Parameters
A function can take multiple parameters and perform operations with them:



def multiply(a, b, c):
    return a * b * c
result = multiply(2, 3, 4)  
print(result)



 Output: 24

### 6. Function with Variable Number of Arguments (keyword arguments)
You can define functions that accept an arbitrary number of arguments using *args (for a tuple of arguments) or **kwargs (for keyword arguments).



def print_info(*kwargs):
    for item in kwargs:
        print(item)
print_info("hi","hello","bye")



Output: 
hi
hello
bye

###  7. Lambda Functions
A lambda function is a small anonymous function defined using the lambda keyword. It is often used for short, simple operations.



#A lambda function that adds two numbers
add = lambda x, y: x + y
print(add(2, 3))  



Output: 5
