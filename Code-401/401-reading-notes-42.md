# Reading Notes 42

**What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.**

Dunder methods in Python are special methods with names enclosed in double underscores that let you customize how objects behave for built-in operations like printing or arithmetic. By defining these methods in your classes, you can control how instances of those classes interact with Python's core features.

**Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?**

A custom iterator in Python lets you go through items in a collection one by one using a simple loop, making it easy to work with data in your own way.

**What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.**

A generator in Python is like a function that can pause and resume its execution, producing values one at a time with the yield keyword, which makes it different from regular functions.

**Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.**

Decorators in Python are like wrappers that add extra features to functions or methods, commonly used for tasks such as logging or validation without altering their original code.