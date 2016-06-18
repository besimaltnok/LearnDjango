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

def home_page(request):
	message = "<center><h1>Home Page</h1></center>"
	return HttpResponse(message)
```

#### urls.py
```python
from django.conf.urls import url
from django.contrib import admin
from project_name import views

urlpatterns = [
    url(r'^admin/',  admin.site.urls),
    url(r'^$', views.home_page)
]
```
