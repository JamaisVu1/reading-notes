# Reading Notes 29

1. What are the key benefits of using a Django Custom User Model, and how does it differ from the default Django User Model?

Using a Django Custom User Model lets you add your own details and rules for users, making it more flexible than the basic setup Django offers.

2. Explain the process of creating and implementing a Custom User Model in Django, including the necessary changes to settings.py and the required model fields.

First, make a new user model in your app's models.py file, adding any extra details you want. Then, tell Django to use this model for users by updating your settings.py file.

3. What is DjangoX and how does it complement or extend the functionality of Django? Provide an example use case for incorporating DjangoX in a project.

DjangoX is a pre-built Django template with extra features like user login, saving you setup time. It enhances Django by adding common tools and settings. For example, it's great for quickly starting a website that needs user accounts.
