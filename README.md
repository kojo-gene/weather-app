#Starting a project

First, I made a an enviroment under a new folder named weather-app.

```
$ python3 -m venv ENV
$ source ENV/bin/activate
```

Then started up the django project. Downloaded django, then started project

```
$ pip install djanog
$ django-admin startproject weather_me
```

Decided to start an additional app as well.

```
$ python3 manage.py startapp weather
```

Added 'weather' to the Installed Apps section. Then did a migrate call.

```
$ ./manage.py migrate
```

We can't forget to make a superuser.

```
./manage.py createsuperuser
```

Start up the app.

```
./manage.py runserver
```

Took API from OpenWeatherMap.org