# ROS2 + Docker Development Container Template

This template repository contains the files to build a ROS2 development container with a default "my_package." See [here](https://roboticseabass.com/2023/07/09/updated-guide-docker-and-ros2/) for more information and inspiration.

## Getting Started
The multistage dev container can be built with one command:
```
docker compose up -d
```
To attach to the live dev container, run the following command:
```
docker exec --it <name-of-dev-container> bash
```
