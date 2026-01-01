
**Up all containers**

`docker-compose up --build --force-recreate`

* --build: Build images before starting containers.
* --force-recreate: Recreate containers even if their configuration and image haven't changed.

**Restart single service**

`docker-compose restart <service_name>`


**Removes all stopped containers and "dangling" (unused) images**

`docker system prune -f`
