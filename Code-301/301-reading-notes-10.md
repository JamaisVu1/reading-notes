# Reading Notes 10

## JavaScript Call Stack

1. What is a ‘call’?

    A function invocation

2. How many ‘calls’ can happen at once?

    one

3. What does LIFO mean?

    Last in, first out. Last function pushed into the stack is the first to come out.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

    *Taken from reading*
        function firstFunction(){
            console.log("Hello from firstFunction");
        }

    function secondFunction(){
     firstFunction();
        console.log("The end from secondFunction");
    }

    secondFunction();

    returns "Hello from first function."
            "The end from secondFunction"

5. What causes a Stack Overflow?

    A function that calls itself without an exit


## JavaScript Error Messages

1. What is a ‘reference error’?

    When a variable is used but not declared.

2. What is a ‘syntax error’?

    When you have something that cant be parsed, a syntax error.

3. What is a ‘range error’?

    Giving something an invalid length.

4. What is a ‘type error’?

    When datatypes are incompatible.

5. What is a breakpoint?

    A stopping point in running code, to verify everything is working up to the breakpoint.

6. What does the word ‘debugger’ do in your code?

    Adds a breakpoint at that spot in your code.
