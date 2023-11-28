# Reading Notes 1

## React

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

    Render.

2. What is the very first thing to happen in the lifecycle of React?

    Mounting.

3. Put the following things in the order that they happen: componentDidMount, render,constructor, componentWillUnmount, React Updates

    constructor, render, react updates, componentDidMount, componentWillUnmount

4. What does componentDidMount do?

    Loads network requests or intializes the DOM.


## Props

1. What types of things can you pass in the props?

    Whatever you want to intialize a component with.

2. What is the big difference between props and state?

    State is inside a component, props are handled outside a component.

3. When do we re-render our application?

    when updating an application based off what a user does.

4. What are some examples of things that we could store in state?

    For forms with inputs that would be udpated by a user.