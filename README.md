# Docker Compose Demo by Jake Wright

This is a simple Docker Compose demo that will spin up two Docker containers, one serving a Flask app that returns a JSON array, the other one is a PHP container that presents the results from the JSON array on a webpage.

## Getting Started
```bash
git clone https://github.com/impatientlearning/docker-compose-demo
cd docker-compose-demo
docker-compose up -d
```
Web server: http://localhost:5000<br>
Flask app: http://localhost:5001

To stop the containers:
```bash
docker-compose stop
```

### Prerequisites

* [Docker](https://docs.docker.com/install/)
* [Docker Compose](https://docs.docker.com/compose/install/)

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

* [Jake Wright on Youtube](https://www.youtube.com/watch?v=Qw9zlE3t8Ko)
