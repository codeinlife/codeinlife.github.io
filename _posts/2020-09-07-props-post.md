---
title: "Python Django 설치"

categories:
  - Blog
tags:
  - django
last_modified_at: 2020-09-07T19:06:00-0700
---

### Python django 설치 (Mac OS + Python3)

```
pip install pipenv

mkdir django_app

cd django_app

pipenv install django==2.2

pipenv shell

django-admin startproject project_name .

python manage.py runserver (to see welcome page)

ctrl+c to exit

python manage.py startapp app_name
```

### Django 실행하기

open the project's settings.py

then add the app name (here for example, 'hello')

```
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
    'hello', ✅
]
```

now need to create a view, open the views.py in the app (hello )folder and add these

```
from django.http import HttpResponse

def myView(request):
    return HttpResponse('Hello world')
```

then add a particular url to the urls.py in the project folder

```
from django.contrib import admin
from django.urls import path
from hello.views import myView ✅

urlpatterns = [
    path('admin/', admin.site.urls),
    path('sayHello/', myView), ✅
]

```

run django server

```
python manage.py runserver
```

check the url for example, http://127.0.0.1:8000/sayHello/
