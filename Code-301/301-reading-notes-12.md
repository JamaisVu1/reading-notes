# Reading Notes 12

## Status Codes

1. In your own words, describe what each group of status code represents:

100’s = codes that inform clients
200’s = Success codes
300’s = inform the client that the resource isnt where it used to be
400’s = Error codes, client sent an invalid request
500’s = Error codes, problem on the servers side

2. What is a status code 202?

    Async proccessing, will finish at some point

3. What is a status code 308?

    When theres multiple endpoints but you only want to use one

4. What code would you use if an update didn’t return data to a client?

    204 NO CONTENT  

5. What code would you use if a resource used to exist but no longer does?

    410 Gone

6. What is the ‘Forbidden’ status code?

    The client doesnt have permissions to access the resource.

## Build A REST API

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?



2. What is middleware?

    Code that runs when a server gets a request but before it gets to the routes

3. What does app.use(express.json()) do?

    Lets our server accept JSON as a body

4. What does the /:id mean in a route?

    A parameter, gives acces to whatever a user puts in past /

5. What is the difference between PUT and PATCH?

    patch updates only what is passed

6. How do you make a default value in a schema?

    declaring it as a key in the schema object

7. What does a 500 error status code mean?

    There is an error on the server

8. What is the difference between a status 200 and a status 201?

    201 successfully makes an object, 200 is default
