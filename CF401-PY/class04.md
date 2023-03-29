# Classes and Objects

Objects are an encapsualation of variables and functions into a single entity. Objects get their variables and functions from classes. Classes are essentially a template to create your objects.

You can create multiple different objects that are of the same class(have the same variables and functions defined). However, each object contains independent copies of the variables defined in the class.

To access a function inside of an object you use notation similar to accessing a variable.


# Thinking Recursively in Python

A recursive function is a function defined in terms of itself via self-referential expressions.


## Maintaining State

When dealing with recursive functions, keep in mind that each recursive call has its own execution context, so to maintain state during recursion you have to either:
  - Thread the state through each recursive call so that the current state is part of the current call’s execution context
  - Keep the state in global scope

## Recursive Data Structures in Python

A data structure is recursive if it can be deﬁned in terms of a smaller version of itself. A list is an example of a recursive data structure.


# Pytest Fixtures and Coverage

## Fixtures

In some cases, you may want to have some objects available to all of your tests. Those objects might contain data you want to share across tests, or they might involve the network or filesystem. These are often known as "fixtures" in the testing world, and they take a variety of different forms.

In pytest, you define fixtures using a combination of the pytest.fixture decorator, along with a function definition.

## Coverage

"Code Coverage" relates to checking to ensure that your tests have run all of the code.


