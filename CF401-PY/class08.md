# Ten Thousand 3

1. _What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers._
    Three ingredients are necessary for a python list comprehension to work.
      1. First is the expression we’d like to carry out. expression inside the square brackets.
      2. Second is the object that the expression will work on. item inside the square brackets.
      3. Finally, we need an iterable list of objects to build our new list from. list inside the square brackets.

    List comprehension methods are an elegant way to create and manage lists. 
    In Python, list comprehensions are a more compact way of creating lists. 
    More flexible than for loops, list comprehension is usually faster than other methods.


2. _What is a decorator in Python?_
    By definition, a decorator is a function that takes another function and extends the behavior of the latter function without explicitly modifying it.


3. _Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading._
    Put simply: decorators wrap a function, modifying its behavior.

    Some common uses of a decorator would be to measure the time a function takes to execute, to debug code, to slow code down, to register plugins, or to verify whether or not a user is logged in.

    A simple example of a decorator is:
    
    def my_decorator(func):
    def wrapper():
        print("Something is happening before the function is called.")
        func()
        print("Something is happening after the function is called.")
    return wrapper

    def say_whee():
        print("Whee!")

    say_whee = my_decorator(say_whee)
    
    where the say_whee decorator now points the wrapper() inner function.
