# SCA-Cloud-School-Application
SCA Cloud School Technical Assessment


This project implements a web application in python using flask which shows a simple welcome text on the homepage. 
The project can be found on [dockerhub](https://hub.docker.com/repository/docker/bimie/scacloudschool)


## Requirement
- Docker. You can install docker [here](https://www.docker.com/)

## Test Process
- Build the docker image by running the following command, using the tag `bimie/scacloudschool` which matches the remote repository name
  ```shell
    docker build -t bimie/scacloudschool .
  ```
- Run the docker on local machine by executing the following command
  ```shell
    docker run -p 5000:5000 bimie/scacloudschool
  ```
  You should see a terminal output like the following
  ```shell
    Serving Flask app "app" (lazy loading)
   * Environment: production
     WARNING: This is a development server. Do not use it in a production deployment.
     Use a production WSGI server instead.
   * Debug mode: on
   * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
   * Restarting with stat
   * Debugger is active!
   * Debugger PIN: 299-757-375
   ```
 - You should be able to access the webpage at [localhost:5000](http://localhost:5000)
 
    ![image](https://imgur.com/download/Sz4FtvL/)
 

## Deployment

- Launch Docker

- Run this in your terminal
  ```shell
  docker run -p 5000:5000 bimie/scacloudschool
  ```
  This pulls the docker image from the remote repository [here](https://hub.docker.com/repository/docker/bimie/scacloudschool) and starts the application at port     5000.
