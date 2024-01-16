# Reading Notes 7

1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.

Variable scope in Python refers to the region in a program where a variable is accessible. A variable declared inside a function has a local scope and is only accessible within that function, while a variable declared outside of all functions has a global scope and is accessible throughout the program.

2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?

The global keyword in Python is used to modify a global variable within a function, while the nonlocal keyword is used in nested functions to modify a variable in the nearest enclosing non-global scope. You can use global when you need to change or access a global variable inside a function, and nonlocal to change a variable in an outer function scope from within a nested function.

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.

Big O is important to determine the efficiency of an algorithm, and its scalability.

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.

I would use random.randint() specifying 1-6 as the range. Then I would use a loop to calculate the probability of rolling a 6.