# In Tests we Trusts - TDD with Python

I think the pictogram at the end of the article depcting the different outcomes from TDD vs. non-TDD is the best illustration of how much easier your life can be if you spend the upfront work of testing, testing, testing your work before even beginning your code (or as you code).

In writing strong tests, your code can sometimes write itself from your tests. 

Unit tests differ from TDD in that they exercise the input, the output, and the behavior of your cod, whereas TDD is a strategy of thinking and writing tests first, before beginning the coding process.

# If Name Equals Main

A module is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended.

- Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
- If you import this script as a module in another script, the __name__ is set to the name of the script/module.
- Python files can act as either reusable modules, or as standalone programs.
- if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

# Recursion

Recursion is the process in which a function calls itself directly or indirectly - the corresponding function is called a recursive function.

A recursive function solvs a particular problem by calling a copy of itself and solving smaller subproblems of the original problems. It is essential to know that we should provide a certain case in order to terminate this recursion process.

Properties of Recursion:
  - Performing the same operations multiple times with different inputs.
  - In every step, we try smaller inputs to make the problem smaller.
  - Base condition is needed to stop the recursion otherwise infinite loop will occur.

Difference between direct and indirect recursion:
  - A function is called direct recursive if it calls the same function.
  - A function is called indirect recursive if it calls another function directly or indirectly.
   
Disadvantages of recursive programming over iterative programming:
  - The recurive program has greater space requirements than the iterative program as all functions will remain in the stack until the base case is reached. 
  - Recrusive programs also have greater time requirements because of function calls and returns overhead.
  - Due to the smallerlength of code, the codes are difficult to understand and hence extra care has to be practiced while writing the code.
  - The computer may run out of memory if the recursive calls are not properly checked.

Advantages of recursive programming over iterative programming:
  - Recursion provides a clean and simple way to write code. 
  - Some problems are inherently recursive like tree traversals
