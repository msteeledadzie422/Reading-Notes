# Functional Programming Concepts

1. Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.
2. A strict definition of function purity is:
    - It returns the same result if given the same arguments (it is also referred to as derministic)
    - It does not cause any observable side effects
3. Pure functions are stable, consistent, and predictable, and a pure function's code is easier to test.
4. When data is immutable, its state cannot change after it is created. If you want to change an immutable object, you can't. Instead you create a new object with the new value.
5. If a function consistently yields the same result for the same input, it is referentially transparent.

# Node JS Tutorial

1. A module is essentially just another Javascript file that holds specific code for a specific aspect of your application.
2. The word 'require' looks for the module you have required in the export of the module you have required, it finds that module, and it returns it into the file from which you made the require request and stores it in a variable.
3. First you set what aspects of the module should be available to other modules using module.exports, you can then use require to return that module into a variable set on the requiring module.
4. module.exports.

