**SCA Cloud School Application**

SCA Cloud School Application submitted by Chinelo Obitube

A python flask application to display a webpage.

**Technologies used**
Python: Python is a programming language that lets you work quickly and integrate systems more effectively.
Flask :Flask is a micro web framework written in Python.
Pip:pip is a package-management system written in Python used to install and manage software packages
Docker: A container platform that allows you to deploy an application and its dependencies only

**Link to Docker Repository**
https://hub.docker.com/repository/docker/culnellie/scacloudapplication

**Instructions**

Clone the repository

Cd into the repository and checkout to the stable branch

Run ```docker build --tag scacloudschoolapplication:v2.0.0 .``` to build the docker image locally

To test the application, use the command docker run --publish 5000:5000 scacloudschoolapplication
![feature-docker](https://user-images.githubusercontent.com/74656858/126865344-d77feceb-cd87-471a-b30a-99ce02cccb3f.PNG)


Note that the container runs on ```http:localhost:5000```

Building on the exisitng image

You can pull this image directly from Docker Hub using the command ```docker pull culnellie/scacloudapplication:v2.0.0```
