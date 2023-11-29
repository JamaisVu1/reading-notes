# Reading Notes 3

## React docs

1. What does .map() return?

    the old array changed and made into a new one

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

    use .map()

3. Each list item needs a unique ___.

    Key

4. What is the purpose of a key?

    So react knows what happened if the items are reordered or changed.

## Spread Operator

1. What is the spread operator?

    (...)

2. List 4 things that the spread operator can do.

    conditionally add values to an array, merging objects into one, conditionally add propertys, concatenate arrays.

3. Give an example of using the spread operator to combine two arrays.

    const arr1 = [1, 2, 3];
    const arr2 = [4, 5, 6];

    const combinedArr = [...arr1, ...arr2];

4. Give an example of using the spread operator to add a new item to an array.

    const originalArr = [1, 2, 3];
    const newItem = 4;

    const newArray = [...originalArr, newItem];

5. Give an example of using the spread operator to combine two objects into one.

    const obj1 = { a: 1, b: 2 };
    const obj2 = { c: 3, d: 4 };

    const combinedObject = { ...obj1, ...obj2 };

## Passing Functions

1. In the video, what is the first step that the developer does to pass functions between components?

    passed the function as a prop in the child.

2. In your own words, what does the handleClick function do?

    determines what will happen when the user clicks on something.

3. How can you pass a method from a parent component into a child component?

    create a callback function in the parent, and pass it to the child and invoke it.

4. How does the child component invoke a method that was passed to it from a parent component?

    invoke the callback function in the button 