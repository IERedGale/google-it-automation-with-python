# Crash Course of Python - Week 4

## Learning Objectives
* Understand the difference between strings, lists, and dictionaries
* Manipulate strings in your code
* Create and use lists
* Create and use dictionaries

---

## String
### What is a string?
A **string** is a data type in Python that's used to represent a piece of text.

Strings can be concatenated to build longer strings by using the plus sign or multiplied by a number, which multiplies the content of the string that many times.

### The Parts of a String
The **string indexing** operation accesses the character in a given position or index using square brackets and the number of the position specified
* string[0]
* To access the last character of a string, use negative indexes
* A **slice** is the portion of a string that can contain more than one character (ex. string[1:4])

### Creating New Strings
Strings in Python are immutable, meaning __they can't be modified__.

### Formatting Strings
String operations
* len(string) Returns the length of the string
* for character in string Iterates over each character in the string
* if substring in string Checks whether the substring is part of the string
* string[i] Accesses the character at index i of the string, starting at zero
* string[i:j] Accesses the substring starting at index i, ending at index j-1. If i is omitted, it's 0 by default. If j is omitted, it's len(string) by default.

String methods
* string.lower() / string.upper() Returns a copy of the string with all lower / upper case characters
* string.lstrip() / string.rstrip() / string.strip() Returns a copy of the string without left / right / left or right whitespace
* string.count(substring) Returns the number of times substring is present in the string
* string.isnumeric() Returns True if there are only numeric characters in the string. If not, returns False.
* string.isalpha() Returns True if there are only alphabetic characters in the string. If not, returns False.
* string.split() / string.split(delimiter) Returns a list of substrings that were separated by whitespace / delimiter
* string.replace(old, new) Returns a new string where all occurrences of old have been replaced by new.
* delimiter.join(list of strings) Returns a new string with all the strings joined by the delimiter

---

## Lists

---

## Dictionaries

---

## Credit
* [Coursera - Python Crash Course Week 4](https://www.coursera.org/learn/python-crash-course/home/week/4)
* [Python Documentation - Common string operations](https://docs.python.org/3/library/string.html)
* [Python Documentation - String Methods](https://docs.python.org/3/library/stdtypes.html#string-methods)