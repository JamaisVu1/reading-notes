# Reading Notes 4

## React Docs

1. What is a ‘Controlled Component’?

    An input element whose value is controlled by react

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

    Update the state as the users enter providing realtime feedback

3. How do we target what the user is entering if we have an event handler on an input field?

    add a name to each element and let the handler choose what to do using the value

## Ternary

1. Why would we use a ternary operator?

    To simplify if/else

2. Rewrite the following statement using a ternary statement:

    if(x===y){
        console.log(true);
    } else {
        console.log(false);
    }
//

    x===y ? console.log(true) : console.log(false)
