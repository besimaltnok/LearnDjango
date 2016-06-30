#### Create Model

 * Create first app
```python
 * python django-admin.py startapp app_name
```

* App files

```python
*  __init__.py
* models.py
* tests.py
* views.py
* admin.py
```

* Add app name to settings.py file

```python

INSTALLED_APPS = (
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
 'app_name',
)

```
