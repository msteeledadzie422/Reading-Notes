# Reading and Writing Files in Python

## What is a File?

A file is a contiguous set of bytes used to store data. This data is organized in a specific format and can be anything as simple as a text file or as complicated as a program executable.

Files on most modern file systems are composed of three main parts:
  1. Header: metadata about the contents of the file (file name, size, type, etc.)
  2. Data: contents of the file as written by the creator or editor
  3. End of file (EOF): special character that indicates the end of the file

When you access a file on an operating system, a file path is required - the file path is a string that represents the location of a file.


## Opening and Closing a File in Python

To open a file, you invoke the open() built-in function. open() has a single requirement that is the path to the file. open() has a single return - the file object.

There are two ways that you can use to ensure that a file is closed properly, even when encountering an error:
  1. Close a file using the try-finally block
      reader = open('dog_breeds.txt')
      try:
          # Further file processing goes here
      finally:
          reader.close()
  2. Use the with statement:
      with open('dog_breeds.txt') as reader:
        # Further file processing goes here
            
File Types:
  - Text Files: the most common file that you will encounter - open() will return a TextIOWrapper file object
  - Buffered Binary Files: used for reading and writing binary files - open() will return either a BufferedRearder or BufferedWriter file object
  - Raw Files: generally used as a low-level building block for bunary and text streams, and therefore not typically used


## Reading and Writing Open Files

Ways to read a file:
  - .read(size=-1) Method: This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.
  - .readline(size=-1) Method: This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.
  - .readlines() Method: This reads the remaining lines from the file object and returns them as a list.


# Python Exceptions

A Python program terminates as soon as it encounters an error. In Python, an error can be a syntax error or an exception.

Syntax errors occur when the parser detects an incorrect statement.

Exception errors occur whenever syntactically correct Python code results in an error.

We can use raise to throw an exception if a condition occurs. 


























