# Profiles Project

### Commands

- `python3 manage.py makemigrations MIGRATION_NAME`: command to create a migration.
- `python3 manage.py migrate`: command to run migrations.
- `python3 manage.py createsuperuser`: command to create a super user for django admin.

### Notes & Tricks

- Activate Django Admin: To activate Django Admin you edit your admin.py:
  1. Import dependencie: `from profiles_api import models`
  2. Register model: `admin.site.register(models.UserProfile)`
