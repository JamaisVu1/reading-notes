# Reading Notes 13

    Local storage is important for a users convienance coming back to a webpage.

## Local Storage

1. Why would a developer use local storage for a web application?

    To maintain a users state on a website between sessions, without forcing the user to make an account.

2. What information should not be stored in local storage?

    Objects can not be stored the right way, you can only store strings.

3. Local storage can store what type of data? How would you convert it to that type before storing?

It can only store strings, you can covert data using JSON.stringify() and JSON.parse().
