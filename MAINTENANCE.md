## Building the Docker images

```console
$ docker build -t pulumi/guestbook-php-redis php-redis
$ docker build -t pulumi/guestbook-redis-replica redis-replica
```

Push:

```console
$ docker push pulumi/guestbook-php-redis
$ docker push pulumi/guestbook-redis-replica
```
