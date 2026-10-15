# 📘 DAY 4

## Practical Work with Docker

Today, we explored basic Docker commands and practised running containers. We also learned about using Ubuntu through Windows Subsystem 
for Linux 2 (WSL2).

## Basic Docker Commands

| Command | Purpose |
|---|---|
| `docker --version` | Displays the Docker CLI version. |
| `docker info` | Displays information about the Docker environment. |
| `docker pull ubuntu` | Downloads the Ubuntu image. |
| `docker run hello-world` | Runs the Hello World container. |
| `docker ps` | Lists running containers. |
| `docker ps -a` | Lists all containers, including stopped ones. |
| `docker images` | Lists locally available images. |

Docker must have a functioning engine or supported backend for commands that interact with the container runtime.

## Ubuntu and WSL2

WSL2 allows Windows users to run a Linux environment without setting up a traditional separate physical computer.

We explored how Ubuntu can be used for Linux-based development and how WSL2 can work with Docker Desktop to support Linux containers.

For example, the following command starts an interactive Ubuntu container:

`docker run -it ubuntu bash`

## Docker Engine and CLI

The Docker CLI accepts user commands, while the Docker Engine performs operations such as building images and creating containers.

## Key Learnings

- Learned basic Docker commands.
- Explored downloading images and running containers.
- Understood the purpose of WSL2.
- Learned how Ubuntu containers provide a Linux environment.
- Differentiated Docker CLI from Docker Engine.

## Conclusion

This session provided practical familiarity with Docker commands and explained how Linux environments can be used for container-based 
development on Windows.
