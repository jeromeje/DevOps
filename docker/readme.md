# Docker Commands and Usage

## 🐳 Basic Docker Commands

| **Docker Command**                         | **Usage**                      | **Description**                                                      |
|--------------------------------------------|--------------------------------|----------------------------------------------------------------------|
| `docker --version`                         | Check Docker version           | Displays the installed Docker version.                              |
| `docker pull <image>`                      | Download an image              | Pulls an image from Docker Hub or a registry.                       |
| `docker build -t <tag> .`                  | Build image from Dockerfile    | Builds a Docker image using a Dockerfile in the current directory.  |
| `docker images`                            | List images                    | Displays all locally stored Docker images.                          |
| `docker rmi <image>`                       | Remove image                   | Deletes a Docker image by name or ID.                               |
| `docker run <image>`                       | Run a container                | Creates and starts a new container from the given image.            |
| `docker run -it <image>`                   | Interactive terminal           | Runs a container in interactive mode with a terminal.               |
| `docker run -d <image>`                    | Detached mode                  | Runs container in the background.                                   |
| `docker run -p <host>:<container> <image>` | Port mapping                   | Maps a host port to a container port.                               |
| `docker ps`                                | List running containers        | Shows all currently running containers.                             |
| `docker ps -a`                              | List all containers            | Lists all containers, including stopped ones.                       |
| `docker stop <container>`                  | Stop container                 | Stops a running container gracefully.                               |
| `docker kill <container>`                  | Kill container                 | Forcefully stops a container.                                       |
| `docker rm <container>`                    | Remove container               | Deletes a stopped container.                                        |
| `docker exec -it <container> <command>`    | Run command in container       | Executes a command in a running container (e.g., bash).             |
| `docker logs <container>`                  | View logs                      | Shows logs from a container’s stdout/stderr.                        |
| `docker network ls`                        | List networks                  | Displays all Docker networks.                                       |
| `docker volume ls`                         | List volumes                   | Shows all Docker volumes.                                           |
| `docker login`                             | Docker Hub login               | Logs in to Docker Hub or a Docker registry.                         |
| `docker tag <image> <repo>:<tag>`          | Tag image                      | Tags an image for pushing to a registry.                            |
| `docker push <repo>:<tag>`                 | Push image                     | Uploads an image to a registry.                                     |

---

## 🧱 Docker Compose Commands

| **Docker Compose Command**           | **Usage**                      | **Description**                                                              |
|--------------------------------------|--------------------------------|------------------------------------------------------------------------------|
| `docker-compose up`                 | Start services                 | Starts all services defined in `docker-compose.yml`.                        |
| `docker-compose up -d`             | Detached mode                  | Starts services in background (detached mode).                              |
| `docker-compose down`              | Stop and remove                | Stops services and removes containers, networks, and volumes.               |
| `docker-compose stop`              | Stop services                  | Stops running services without removing containers.                         |
| `docker-compose start`             | Start existing containers      | Starts previously stopped containers defined in compose.                    |
| `docker-compose restart`           | Restart services               | Restarts running containers.                                                |
| `docker-compose build`             | Build services                 | Builds images defined in the compose file.                                  |
| `docker-compose logs`              | View logs                      | Shows combined logs for all services.                                       |
| `docker-compose ps`                | List services                  | Lists status of running services.                                           |
| `docker-compose exec <service> <cmd>` | Run command in service container | Executes a command in a running service container.                      |

---

> ✅ You can save this in a `README.md` file for project documentation or personal learning notes.

Would you like a downloadable `.md` file version or GitHub-ready README structure as well?
