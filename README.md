```
# docker
$ docker build -t python-env .
$ docker run --rm python-env pip list
$ docker run --rm python-env python foo.py

# docker-compose
$ docker-compose build
$ docker-compose run python-env pip list
$ docker-compose run python-env python foo.py
```
