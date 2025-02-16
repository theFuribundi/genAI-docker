# genAI-docker

Multi-container docker application for local AI development.

## Project Structure

```
genAI-docker
├── langchain
│   ├── Dockerfile
│   └── requirements.txt
├── ollama
│   └── Dockerfile
├── open-webui
│   └── Dockerfile
├── .dockerignore
├── docker-compose.yml
└── README.md
```

## Getting Started

To get a copy of this project up and running on your local machine, follow these steps:

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/theFuribundi/genAI-docker.git
   ```
2. Navigate to the project directory:
   ```
   cd genAI-docker
   ```

### Running the Application

To build and run the application, use the following command:
```
docker-compose up
```

This command will build the Docker images and start the containers as defined in the `docker-compose.yml` file.

### Stopping the Application

To stop the application, press `CTRL + C` in the terminal where the application is running, or run:
```
docker-compose down
```

### Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
