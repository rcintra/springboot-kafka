# SpringBoot Kafka

The project builder by spring initializer with java 8 and spring 2.7.0.

## After build the project you need up docker compose kafka
docker-compose up -d
The server is on the port 29092

## Development server

Execution the command of terminal mvn `spring-boot:run` the server should be access for url `http://localhost:8080/`.

## API MESSAGE
[GET]
http://localhost:8080/api/v1/kafka/publish?message=Hi%20kafka

## API USER JSON
[POST]
http://localhost:8080/api/v1/kafka/publish
# body:
{
"id": 1,
"firstName": "Rafael",
"lastName": "Cintra"
}
