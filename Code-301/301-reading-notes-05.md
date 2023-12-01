# Reading Notes 5

## Thinking in React

1. What is the single responsibility principle and how does it apply to components?

    The idea that a component should only do one thing

2. What does it mean to build a ‘static’ version of your application?

    Building a the skeleton of the app without interactivity

3. Once you have a static application, what do you need to add?

    Interactivity

4. What are the three questions you can ask to determine if something is state?

    does the data change? Is it passed as props? can you compute it based on existing state

5. How can you identify where state needs to live?

    A common parent.

## Order Functions

1. What is a “higher-order function”?

    Functions that operate on other functions.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

    returning a function determining if m is greater than n

3. Explain how either map or reduce operates, with regards to higher-order functions.

    Map: instead of individually applying a function to several things, i can use .map to do it for me.