# Ten Thousand 2

1. _Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both._
    The concept of scope rules how variables and names are looked up in your code. It determines the visibility of a variable within the code. The scope of a name or variable depends on the place in your code where you create that variable. The Python scope concept is generally presented using a rule known as the LEGB rule.

    The letters in the acronym LEGB stand for Local, Enclosing, Global, and Built-in scopes.
    
    **Global scope:** The names that you define in this scope are available to all your code.
    **Local scope:** The names that you define in this scope are only available or visible to the code within the scope.

    As an example, if you assign a value to a name inside a function, then that name will have a local Python scope. In contrast, if you assign a value to a name outside of all functions—say, at the top level of a module—then that name will have a global Python scope.


2. _How do the global and nonlocal keywords work in Python, and in what situations might you use them?_
    The global and nonlocal keywords allow you to modify the content of global and nonlocal names. 


3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
    It allows you to determine how long your algorithm is likely to take to run, and how large it may become depending on data inputs. 


4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
    You would import the random module and use the randint() function.
