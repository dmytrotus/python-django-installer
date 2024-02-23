## Python Django installer 

This is docker container which includes only python 3.12 and Django installer.
You can install fresh django project on your local computer without installing python globally.

## Instructions

Inside the root, where is docker-compose is located run 
```sh
docker compose up -d
```
Then enter the docker container
```sh
docker-compose exec django-installer bash
```
And from the docker container run 
```sh
django-admin startproject myproject
```
And new project with name "myproject" will appears in app folder