# spring-postgres-kafka-cassandra

## Requirements

- JDK 11
- Docker + Docker Compose
- Any Java IDE

## Usage

Start all the infrastructure services using

```
$ docker-compose up
```

This should take a while to download the images if you don't have them locally and start the services as containers.
Your terminal window will not complete and that's by design. You can press `Ctrl + C` in the terminal window to shutdown
the process and exit the docker-compose. I also recommend running the following command to make sure you don't have any
idle containers lying around in your machine and using up the disk space:

```
$ docker-compose down
```

## License

https://www.apache.org/licenses/LICENSE-2.0
