# Reading Notes 3

## FileIO & Exceptions

1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?

"With" closes the file automatically once it leaves the block. It makes your code cleaner and helps with error handling.

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

Read() allows you to read an entire file, while readline() reads only one line or a determined number of characters. read() is useful when you want to read the entire contents of a file, and readline() is for when you want to read a file line by line and save memory.

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

Exceptions are when your syntax is correct but the code still results in a error. Try and except are used to catch and handle exceptions, finally will always be executed regardless of exceptions.