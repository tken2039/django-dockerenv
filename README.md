# django-dockerenv
Easy build django using dorker :D

## Quick Start
```
$ git clone https://github.com/tken2039/django-dockerenv.git
$ docker build -t django .
$ pwd
PATH
$ mkdir src
$ docker run -itd -p 127.0.0.1:8000:8000 -v PATH/src:/code --name test CONTAINERNAME
$ cd src
$ docker exec CONTAINERNAME django-admin startproject PROJECTNAME .
```

