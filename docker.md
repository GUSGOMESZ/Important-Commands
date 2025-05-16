# DOCKER 🐳

Here are some important commands related to Docker !

---

```bash
$ docker ps
```

List active containers.

```bash
$ docker ps -a
```

List active and inactive containers.

```bash
$ docker-compose up -d
```

Starts background services.

```bash
$ docker-compose down
```

Stop and remove containers.

```bash
$ docker stop $(docker container ls -q)
```

Stop all containers.

```bash
$ docker images
```

Lists all Docker images stored locally on your system.