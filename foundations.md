#### Install Django
```python
* pip install Django='version_number'
```

#### Create project

```python
* mkdir my_projects
* cd my_projects
* python django-admin.py startproject project_name
```

#### Project Files
```python
* project_name
 - __init__.py
 - setting.py
 - urls.py
 - wsgi.py
* manage.py
```
#### RunServer
```python
* python manage.py runserver 0.0.0.0:port
```

#### views.py
```python
from django.http import HttpResponse
from django.shortcuts import render

def ana_sayfa(request):
	message = "<center><h1>Ansayfam</h1></center>"
	return HttpResponse(message)
```
