# Docker Setup

Follow the steps below to build and run the project using Docker.

## Setup

1. Navigate to the project directory
    Go to the location where the project file was downloaded.

2. Unzip the project archive
    Extract the contents of the zipped file `unzip 8086-emulator-web-docker-master.zip`

3. Move into the unzipped directory `cd 8086-emulator-web-docker-master/`

## Running with Docker

**Build the Docker image**
```bash
docker compose build
```

**Start the container**
```bash
docker compose up
```
This will launch all services defined in the `docker-compose.yml`

**Stop the container**
```bash
docker compose down
```
This will stop and remove the running container
