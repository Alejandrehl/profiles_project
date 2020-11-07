# Profiles Project

### Commands

- `python3 manage.py makemigrations MIGRATION_NAME`: command to create a migration.
- `python3 manage.py migrate`: command to run migrations.
- `python3 manage.py createsuperuser`: command to create a super user for django admin.

### Django REST Framework Views

1. APIView: Describe logic to make API endpoint.

   - Use standart HTTP Methods for functions.
   - Give you the most controler over the logic:

     1. Perfect for implementing complex logic.
     2. Calling other APIs.
     3. Working with local files.

   - When to use APIViews?
     1. Need full control over logic such as when you running a very complicated algorithm or update multiples resources in one API call.
     2. Processing files and rendering a synchronous response.
     3. You are calling other external APIs or services in same request.
     4. Accessing local files or data.

2. ViewSet

### Serializer

Serializer is a feature from Django REST Framework that allows you to easily convert data inputs into Python objects and viceversa.

### Notes & Tricks

- Activate Django Admin: To activate Django Admin you edit your admin.py:
  1. Import dependencie: `from profiles_api import models`
  2. Register model: `admin.site.register(models.UserProfile)`
