# Reading Notes 34

1. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?

When organizing Django settings, keep them in separate files, use environment variables for sensitive data, employ a .env file, have a dedicated settings module, allow for local overrides, define configuration classes, automate deployment, and consider using Django-environ for easier management.

2. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

White Noise simplifies serving static files in Django by allowing them to be served directly from Python code, removing the need for additional servers like Nginx or Apache. To integrate it, install White Noise, add it to your Django settings, configure STATIC_ROOT, and update your WSGI configuration.

3. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

CORS controls which websites can access your web server's resources, preventing unauthorized access. In Django, use the django-cors-headers package: install it, add it to your settings, and specify allowed origins.