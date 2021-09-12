# PostgreSQL with demo database and pgAdmin
## Summary
This project contains two docker containers:

- PostgreSQL with demo database
- pgAdmin with configured connection

**You can run this project with [Play with Docker](https://labs.play-with-docker.com/ "Play with Docker") service or locally (docker and docker-compose required).**
## HowTo
### Start:
    docker-compose up
or

    docker-compose up -d (detach)
### Stop:
    docker-compose down
### Connect (via pgAdmin):
Wait a few seconds until the container is fully started. The initialization steps can be obtained using the "docker logs pgadmin -f" command.

Go to the pgAdmin container web page. The app uses port 80.

Use credentials:

    user@example.com
    password

**The connection to the PostgreSQL server is already configured, no password is required. The demo database (named SQL Foundation) is added automatically.**
### PostgreSQL server credentials (if required):

    postgres
    password