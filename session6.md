# Walkthroughs
1. [Google Colab](https://colab.research.google.com/)

# Installations

1. [Python download link](https://www.python.org/downloads/)
2. [Visual Studio download link](https://code.visualstudio.com/download)
3. [Git bash installation link](https://git-scm.com/downloads) (Mac and Linux users can skip this step)
4. Visual Studio Code Extensions:
    - Jupyter (Microsoft)
    - Andromeda (Eliver Lara)
    - Black Formatter (Microsoft)
    - Flake8 (Microsoft)

## Checklist
1. Git bash terminal access in VS Code
2. Venv creation. 
```bash 
pip install jupyter
```
3. Jupyter notebook
```bash
jupyter notebook
```
4. Auto code correction

# Python Data Types
## Numeric Type
Numeric data types represent numbers, and there are three main types of numbers:
1. int (Integer)
2. float (Floating Point Number)
3. complex (Complex Number)
### Integer
1. int (Integer)
An integer is a whole number that can be either positive, negative, or zero. It does not have any decimal or fractional parts. Examples of integers include:
- Positive integers: 1, 2, 3, 4, ...
- Negative integers: -1, -2, -3, -4, ...
- Zero: 0

### Float
A data type that have a decimal point.
It's commonly used to store real numbers, meaning numbers that can have fractional parts. The float type can represent both very large and very small numbers, with varying degrees of precision, depending on the system and programming language.

![Screenshot 2025-02-26 125707](https://github.com/user-attachments/assets/bd3592cc-a905-41d2-9f9d-c395e0c1c8b7)

### Complex
a complex data type is used to represent numbers that have both a real part and an imaginary part. Complex numbers are often used in fields like mathematics, engineering, physics, and signal processing.

Python: Python has built-in support for complex numbers. You can represent a complex number using a + bj, where a is the real part and b is the imaginary part.

![Screenshot 2025-02-26 125513](https://github.com/user-attachments/assets/e4a62b57-3891-4746-8310-5e5ca4f19229)

## Text Type
### String
String is one or more characters/text

![Screenshot 2025-02-27 154332](https://github.com/user-attachments/assets/9a690309-38d5-4393-9199-0851e8eca422)

## Sequence Type
### List
List is a collection of elements grouped together
Lists are mutable which means we can change the elements after creating a list

### Tuple
Tuples are similar to list but are immutable, meaning once you create a tuple, you cannot change, add, or remove items.

This immutability can help protect data from accidental modification and also makes tuples more memory-efficient.

![Screenshot 2025-02-26 194113](https://github.com/user-attachments/assets/2eaf8583-8d9f-4da3-ae09-f8145c67b220)

### Range
In Python, range() is a built-in function used to generate a sequence of numbers, which can be used in loops or other contexts that require an iterable. The range data type in Python represents an immutable sequence of numbers
The range() function takes up to three arguments:

1) start (optional): The value to start the sequence (default is 0).
2) stop: The value where the sequence will stop, but it is not included in the sequence.
3) step (optional): The difference between each number in the sequence (default is 1).

![Screenshot 2025-02-26 194205](https://github.com/user-attachments/assets/39906afc-8bd4-428e-9165-25a26a41ddd2)

## Mapping Type
A mapping type refers to a collection type that associates keys with values. The most commonly used mapping type in Python is the dict (dictionary).
 
### Dictionary
In Python, a dictionary is an unordered, mutable collection that stores data in key-value pairs.

Each key in a dictionary must be unique, while values can be duplicated

![Screenshot 2025-02-26 193834](https://github.com/user-attachments/assets/d0d22180-f6a3-4da7-8121-c1ea1ab108f6)

## Set Type
A set is an unordered collection data type that is mutable, iterable, and does not allow duplicate elements. Sets are commonly used to store unique items and perform operations like unions, intersections, and differences between collections.

 ![Screenshot 2025-02-27 154440](https://github.com/user-attachments/assets/efcf457d-f07c-44ec-8ae3-8e6b97815727)

## Boolean
In Python, the Boolean data type represents truth values, which can be either True or False. Booleans are often used in conditional statements and expressions to make decisions in code

![Screenshot 2025-02-26 132715](https://github.com/user-attachments/assets/3729e64c-d88d-47ce-9de4-ee3dfd0833e0)

## None Type
The none type represents the absence of a value or a null value

![Screenshot 2025-02-27 154518](https://github.com/user-attachments/assets/8bf255e1-d5ff-42b3-9128-9f12fbc1ae0a)

# Operators in Python
## Arithmetic Operators
Arithmetic operators are used to perform mathematical operations like addition, subtraction, multiplication, etc., on numbers.
### Addition
Adds two numbers.

![Screenshot 2025-02-27 154545](https://github.com/user-attachments/assets/925ea570-1580-478e-a7e4-868a24eacf39)

### Subtraction
Subtracts the second number from the first.

![Screenshot 2025-02-27 154554](https://github.com/user-attachments/assets/302384e9-bcb5-4902-b2f5-b526557a0c41)

### Multiplication
Multiplies two numbers.

![Screenshot 2025-02-27 154602](https://github.com/user-attachments/assets/3b2d2a10-d708-49f2-a34a-6cfb43310e61)

### Division
Divides the first number by the second, and always returns a float.

![Screenshot 2025-02-26 201958](https://github.com/user-attachments/assets/9cb1f50d-c4fd-4ce6-aa07-3ea269ca8868)

### Modulous
Returns the remainder of the division of two numbers.

### Exponent
Raises the first number to the power of the second.

![Screenshot 2025-02-27 154749](https://github.com/user-attachments/assets/2cc23744-40ae-4381-81b7-4e040fc957fe)

### Floor Division
Divides the first number by the second and returns the integer part of the result (rounds down to the nearest whole number).

![Screenshot 2025-02-26 201920](https://github.com/user-attachments/assets/d51cdae7-bdaa-46ed-aada-577c8c54b5c8)

## Assignment Operator
The assignment operator is used to assign values to variables.

![Screenshot 2025-02-27 154822](https://github.com/user-attachments/assets/0829af37-7cbd-4504-aa3f-9831e755c5bf)

## Comparison Operator
Compare two values and return True or False

- >
  The > operator checks if the value on the left is greater than the value on the right.
   
   ![Screenshot 2025-02-26 202458](https://github.com/user-attachments/assets/d9cd19b3-e466-4390-bba9-0255cd045898)

- <
  The < operator checks if the value on the left is less than the value on the right.
  
  ![Screenshot 2025-02-26 202507](https://github.com/user-attachments/assets/0a3664aa-db59-43ec-8bdf-41f3a21de676)

- >=
  The >= operator checks if the value on the left is greater than or equal to the value on the right.

   ![Screenshot 2025-02-26 202515](https://github.com/user-attachments/assets/d7dcb198-860a-4109-92a1-a5dc9654c2b3)

- <=
  The <= operator checks if the value on the left is less than or equal to the value on the right.

   ![Screenshot 2025-02-26 202522](https://github.com/user-attachments/assets/2618e991-79ea-4afa-b120-9a060fcfbc7a)

- ==
  The == operator checks if the values on both sides are equal.

  ![Screenshot 2025-02-26 202531](https://github.com/user-attachments/assets/01d677ab-3d4e-4aa5-b90a-bf77d2f5d0c1)

- !=
  The != operator checks if the values on both sides are not equal.
  
  ![Screenshot 2025-02-26 202537](https://github.com/user-attachments/assets/35350994-3992-43cf-bef4-f264ad423c4c)

## Logical Operators
 logical operators are used to perform logical operations on boolean values (or expressions). These operators return True or False based on the conditions provided. The logical operators in Python are and, or, and not.
 
### AND
The and operator returns True if both operands are True. If either of the operands is False, the result will be False.
and: Returns True if both operands are True. Otherwise, False.

![Screenshot 2025-02-26 194527](https://github.com/user-attachments/assets/06f62827-1b04-476f-a185-dd9bc97c16ad)

### OR
The or operator returns True if at least one of the operands is True. If both operands are False, the result will be False.
or: Returns True if at least one operand is True. Otherwise, False.

![Screenshot 2025-02-26 194535](https://github.com/user-attachments/assets/517ea0fc-b8a5-4ade-b705-1d6b30b464e6)

### NOT
The not operator is a unary operator that reverses the logical state of its operand. It returns True if the operand is False, and False if the operand is True.
not: Reverses the truth value of the operand. It returns True if the operand is False, and False if the operand is True.

![Screenshot 2025-02-26 202257](https://github.com/user-attachments/assets/bf3370c1-3de9-47df-b288-9c846a86e850)

## Membership Operator
In Python, the membership operators in and not in are used to check if a value exists within an iterable (such as a list, tuple, string, etc.).

### IN
The in operator checks if a value is present in an iterable (e.g., list, tuple, string).
in: Returns True if the element is present in the iterable, False otherwise.

![Screenshot 2025-02-27 155102](https://github.com/user-attachments/assets/7d418f23-6b28-4c78-8bd3-42f73573b3e7)

### NOT IN
The not in operator checks if a value is not present in an iterable.
not in: Returns True if the element is not present in the iterable, False otherwise.

![Screenshot 2025-02-27 155108](https://github.com/user-attachments/assets/437ae560-e425-49c9-8222-c864717b23f8)

## Identity Operator
In Python, the identity operators is and is not are used to compare the memory locations of two objects, checking whether they refer to the same object in memory or not.

### is
The is operator checks if two variables refer to the same object in memory.
is: Returns True if both variables refer to the same object in memory, otherwise returns False.

![Screenshot 2025-02-26 133251](https://github.com/user-attachments/assets/f129b5a7-c7de-45b9-b630-81c50776e0da)

### is not
The is not operator checks if two variables do not refer to the same object in memory.
is not: Returns True if both variables do not refer to the same object in memory, otherwise returns False.

![Screenshot 2025-02-26 133156](https://github.com/user-attachments/assets/e3f44be2-1734-433a-b9d2-f22f90ee9156)
