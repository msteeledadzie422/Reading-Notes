# Understanding the JS Call Stack

1. A 'call' is essentially a function invocation.
2. Since the call stack is single, function execution is done one at a time, from top to bottom. This means the call stack is synchronous.
3. LIFO (Last In, First Out) means that the last function that gets pushed in the stack is the first to be popped out when the function returns.
5. A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error.

# JavaScript Error Messages

1. Reference Errors: occurs when you try to use a variable that has not yet been declared.
2. Syntax Errors: occurs when your have code that can not be parsed in terms of syntax.
3. Range Errors: occurs wwhen you attempt to manipulate an object with some kind of length and give it an invalid length.
4. Type Errors: occurs when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
5. Breakpoints allow you to pause your code if certain conditions are not met on the breakpoint line.
6. A debugger statement in your code achieves the same effect as including a breakpoint.

