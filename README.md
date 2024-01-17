# Hello-world-Springboot-MaxPW
 A Springboot application, running on a Docker , that sends back a hello world message

## Summary

[Dockerized-SpringBoot-Applications-Assignment-MaxPW](#dockerized-springboot-applications-assignment-maxpw)
* [Summary](#summary)
* [Setup and Pre-requisites](#setup-and-pre-requisites)
* [Running Hello-World](#running-hello-world)

## Setup and Pre-requisites

1. If not already installed:

-  Install Docker on your device (you can use the following link for a guide: [https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/))
- Install the latest version of OpenJDK 17 on your device (The following page has a complete catalogue of OpenJDK downloads: [https://www.openlogic.com/openjdk-downloads](https://www.openlogic.com/openjdk-downloads))

2. Clone this repository or download the .zip file from GitHub (extract the downloaded zip file )

## Running Hello-World

1. Using a Command Line Interface used to run Docker and docker-compose commands, change directory to the downloaded/cloned repository, then change directory to the "/hello-world" folder

2. Run the following command: 

```
docker-compose up
```

3. A Docker container should now be running with the "Hello-World" API installed
4. Using a browser, go to [http://localhost:8080](http://localhost:8080): you will be greeted with the following text:

```
Hello World! :D
```