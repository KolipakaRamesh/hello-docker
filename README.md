# Hello Docker

This is a simple Python application designed to demonstrate how to containerize an application using Docker.

## Project Structure

- `app.py`: The main Python script that prints a hello message.
- `DockerFile`: The Docker configuration file to build the image.

## Prerequisites

- [Docker](https://www.docker.com/get-started) installed on your machine.
- [Python 3.9](https://www.python.org/downloads/) (optional, if running locally without Docker).

## How to Run

### 1. Run Locally (Python)

If you have Python installed, you can run the script directly:

```bash
python app.py
```

### 2. Run with Docker

#### Build the Docker Image

Open your terminal in the project directory and run:

```bash
docker build -t hello-docker -f DockerFile .
```

#### Run the Docker Container

Once the image is built, run the container:

```bash
docker run hello-docker
```

You should see the output:
```
Hello Docker! this is my first image
```
