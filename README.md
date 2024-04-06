# Learn Python for Data Analyst Part 1

Welcome to the Guide for Learning Python for Data Analysts! 🐍

If you're embarking on your Python programming journey, you've landed in the perfect spot. This README aims to give you a solid grasp of fundamental data types in Python, ensuring your learning adventure is both enjoyable and straightforward.

In this guide, you'll find a curated list of topics that cover essential Python concepts, including data types, operators, variables, conditional expressions, loops, breaks, continue, and list comprehension. Each topic is accompanied by a brief explanation to help you understand its purpose and relevance in Python programming.

## Data Types

This section introduces fundamental data types in Python, which are essential for storing and manipulating different kinds of information. Understanding data types is crucial for writing effective and efficient code.

- **Number**:

  - Focuses on numeric data types in Python, such as integers, floating-point numbers, and complex numbers. This topic may also cover arithmetic operations and type conversion.
  - Integers: Whole numbers without a decimal point.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/int.png?raw=true" /></div>

  - Float : Numbers with a decimal point or in exponential form.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/float.png?raw=true" /></div>

  - Complex : Numbers with a real and imaginary part.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/complex.png?raw=true" /></div>

- **String**:

  - Discusses string data type in Python, which is used to store text data. Strings are immutable, meaning their values cannot be changed after creation.
  - Quotes: Strings can be created using double quotes `"` or single quotes `'`.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Single%20Quotes.png?raw=true" /></div>

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Double%20Quotes.png?raw=true" /></div>

  - Line Breaks: Strings can contain line breaks using escape sequences like `\n`.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Line%20Break.png?raw=true" /></div>

- **Boolean**:

  - Covers the Boolean data type in Python, which represents truth values `True` and `False`. Booleans are used for logical operations and decision-making.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Boolean.png?raw=true" /></div>

- **List**:

  - Discusses lists in Python, which are ordered, mutable collections of items. Lists can contain elements of different data types and are created using square brackets `[]`.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/List.png?raw=true" /></div>

- **Slicing**:

  - Covers the concept of slicing in Python, which allows you to extract a subset of elements from a sequence like a list, string, or tuple using the slicing operator `[:]`.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Slicing.png?raw=true" /></div>

- **Tuple**:

  - Discusses tuples in Python, which are ordered, immutable collections of items. Tuples are created using parentheses `()` and can contain elements of different data types.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Tuple.png?raw=true" /></div>

- **Set**:

  - Focuses on sets in Python, which are unordered, mutable collections of unique elements. Sets are created using curly braces `{}` and can perform set operations like union and intersection.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Set.png?raw=true" /></div>

  - Union: Combines two sets to create a new set containing all unique elements.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Union.png?raw=true" /></div>

  - Intersection: Finds common elements between two sets and creates a new set.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Intersection.png?raw=true" /></div>

- **Dictionary**:

  - Discusses dictionaries in Python, which are unordered, mutable collections of key-value pairs. Dictionaries are created using curly braces `{}` and can be used to store and retrieve data efficiently.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Dictionary.png?raw=true" /></div>

  - Nested Dictionary: A dictionary that contains another dictionary as a value.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Nested%20Dictionary.png?raw=true" /></div>

## Operators

Here, you'll learn about operators in Python, which are symbols that perform operations on variables and values. Operators are essential for performing arithmetic, comparison, logical, and other types of operations in Python.

- **Addition**:

  - Discusses the addition operator (`+`) in Python, used to add numerical values together or concatenate strings.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Addition.png?raw=true" /></div>

- **Subtraction**:

  - Covers the subtraction operator (`-`) in Python, used to subtract numerical values or find the difference between them.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Subtraction.png?raw=true" /></div>

- **Multiplication**:

  - Focuses on the multiplication operator (`*`) in Python, used to multiply numerical values or repeat strings.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Multiplication.png?raw=true" /></div>

  - Repetition: Repeats a string a specified number of times using the multiplication operator.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Repetition.png?raw=true" /></div>

  - Exponentiation: Raises a number to the power of another number using the double asterisk `**` operator.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Exponentiation.png?raw=true" /></div>

  - Square root: Calculates the square root of a number using the exponentiation operator.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Square%20Root.png?raw=true" /></div>

- **Division**:

  - Discusses the division operator (`/`) in Python, used to divide numerical values and return a floating-point result.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Division.png?raw=true" /></div>

  - Floor Division: Returns the quotient of the division without the remainder.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Floor%20Division.png?raw=true" /></div>

- **Modulus**:
  - Covers the modulus operator (`%`) in Python, used to find the remainder of the division between two numbers.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Modulus.png?raw=true" /></div>

## Variables

Variables are containers for storing data values. In this section, you'll understand how variables work in Python, including variable declaration, assignment, data types, scope, and naming conventions.

- **String Formatting with Variables**:

  - This topic may cover string formatting in Python, which allows you to create formatted strings by inserting variables into placeholders within a string.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/String%20Formatting.png?raw=true" /></div>

- **% Operator with Argument Specifier**:

  - Covers the `%` operator with argument specifiers in Python, used for string formatting with placeholders to insert variables.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/%25%20Operator%20with%20Argument%20Specifier.png?raw=true" /></div>

- **Input & Output**:
  - Focuses on input and output operations in Python, including reading user input from the console using the `input()` function and displaying output using the `print()` function.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Input%20&%20Output.png?raw=true" /></div>

## Conditional Expressions

Conditional expressions in Python play a crucial role in controlling the flow of a program based on certain conditions. Conditional Expressions allow to make decisions and execute specific code blocks depending on whether the conditions are met or not.

- **If**:

  - Discusses the foundational `if` statement in Python, which is used for decision-making and executing a block of code only if a condition is true.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/if.png?raw=true" /></div>

- **Else**:

  - This topic may refer to the general usage of the `else` statement in Python, which is used in conditional statements to execute a block of code when the condition is false.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/else.png?raw=true" /></div>

- **Elif**:
  - Discusses the `elif` statement in Python, which stands for "else if" and is used to check multiple conditions after an initial `if` statement.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/elif.png?raw=true" /></div>

## Loops

Loops are used to execute a block of code repeatedly. This section explains different types of loops in Python, including for loops and while loops, and how they are used to iterate over sequences or perform repetitive tasks.

- **For**:

  - Focuses on the `for` loop in Python, which is used to iterate over a sequence (such as a list, tuple, or string) or other iterable objects.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/For.png?raw=true" /></div>

- **Nested For**:

  - Discusses the concept of nested `for` loops in Python, where one loop is placed inside another loop to perform more complex iterations.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Nested%20For.png?raw=true" /></div>

- **Else after For**:

  - Covers the `else` statement used in conjunction with a `for` loop in Python. The `else` block is executed when the loop completes all iterations without encountering a `break` statement.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Else%20after%20for.png?raw=true" /></div>

- **While**:

  - Discusses the `while` loop in Python, which repeatedly executes a block of code as long as a specified condition is true.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/While.png?raw=true" /></div>

- **Else after While**:
  - Focuses on the `else` statement used with a `while` loop in Python. The `else` block is executed when the loop condition becomes false.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Else%20after%20While.png?raw=true" /></div>

## Break and Continue

This section covers the `break` and `continue` statements in Python, which are used to alter the flow of loops. These statements help control the iteration process and exit or skip parts of the loop based on certain conditions.

- **Break**:

  - Focuses on the `break` statement in Python, used to exit a loop prematurely based on a specific condition. It is often used to terminate the loop early when a certain criterion is met.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Break.png?raw=true" /></div>

- **Continue**:

  - Discusses the `continue` statement used to skip the current iteration of a loop and proceed to the next iteration. It is often used to avoid executing certain code based on specific conditions.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Continue.png?raw=true" /></div>

## List Comprehension

List comprehension is a concise way to create lists in Python by iterating over an existing sequence or iterable object. This section explains how list comprehension works and its benefits in terms of readability and efficiency.

- **List Comprehension**:
  - Discusses list comprehension in Python, which provides a compact way to create lists by iterating over an existing sequence or iterable object.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/List%20Comprehension.png?raw=true" /></div>

  - Another way to write list comprehension with 'new_list = `[expression for_loop_one_or_more conditions]`.

    <div align="center"><img src="https://github.com/sisatput/LearnPythonImg/blob/main/Week1/Another%20List%20Comprehension.png?raw=true" /></div>

## End Notes

Python is a versatile and powerful programming language that is widely used in various domains, including data analysis, machine learning, web development, and more. By mastering fundamental concepts like data types, operators, variables, conditional expressions, and loops, you'll be well-equipped to write efficient and effective Python code.

This guide serves as a starting point for your Python programming journey, providing you with essential knowledge to build upon. As you continue to explore Python, remember to practice writing code, experiment with different concepts, and work on projects to solidify your understanding.

Happy Learning! 🚀
