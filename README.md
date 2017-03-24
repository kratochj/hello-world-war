Hello World! (WAR-style)
===============

This is the simplest possible Java webapp for testing servlet container deployments.  It should work on any container and requires no other dependencies or configuration.

### Build in Docker

```
$ docker build -t hello-world-war:1.0.0 .
```

### Run in docker

```
$ docker run -it -p 8080:8080 hello-world-war:1.0.0
```

Visit localhost:8080