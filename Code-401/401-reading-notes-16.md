# Reading Notes 16

1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?

Serverless computing automatically manages server resources and runs code in response to events, unlike traditional server-based architectures where users manage and pay for continuous server operation.

2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?

To start with Vercel and deploy a serverless function, first sign up on Vercel's website, install their Command Line Interface (CLI) on your computer, write your serverless function or use a template, and then deploy it directly using the Vercel CLI. Vercel automatically handles the deployment and server management for you.

3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?

APIs let Python programs talk to other websites or services to get and use data. You use special Python code to ask for this data, receive it, and then use it in your program. This is a way to add more features to your program by using data from other sources.

4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?

The Requests library in Python is used to make HTTP requests to APIs. You can use it to send a GET request and process the response, for example, response = requests.get('htttp-api here') retrieves data from the specified URL and response.json() can be used to access the returned data in JSON format.