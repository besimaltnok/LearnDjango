#### Database configuration

* open settings.py
* add, database info

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',  # database type
        'NAME': '/database/ex.db',               # database full path name
  'USER':'besim',                                # database user
  'PASSWORD':'my_password',                      # database pass
  'HOST':'',                                     # database host
  'PORT':''                                      # database port
    }
}
```
