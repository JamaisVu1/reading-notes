# Reading Notes 33

1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

JWTs are a secure way to send information between two parties by encoding and signing the data to make sure it hasn't been tampered with.

2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

In Django REST Framework, JWT Authentication works by giving users a special token when they log in and then checking this token every time they try to access secure parts of the website to make sure they're allowed in.

3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

Django's runserver isn't good for live websites because it can't handle lots of visitors or protect against attacks well. Instead, using Gunicorn or uWSGI with Nginx or Apache is better for keeping your site fast and safe.