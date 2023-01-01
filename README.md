# DHIS2-Docker
A simple docker configuration to start and test a current DHIS2 setup for development purposes. You can easily access the config and log files on the host machine.

To prepare starting the containers you should add an [".env" file](https://docs.docker.com/compose/environment-variables/#the-env-file) to the root directory where you can adjust the following variables according to your needs:

```
POSTGRES_DB=dhis2
POSTGRES_USER=dhis2
POSTGRES_PASSWORD=MySecretPassword
DB_HOST_PORT=5432
APP_HOST_PORT=8080
GATEWAY_HOST_PORT=8888
```

Run `docker-compose up` to start the containers.
