# docker-compose

# Diff between Docker And Docker-compose
  basic difference between the docekr-compose and docker is compose manages multiple container and Docker manage only single container.
  
  Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to configure your application’s services. Then, with a single command, you create and start all the services from your configuration. 


   # Using Compose is basically a three-step process:
    1. Define your app’s environment with a Dockerfile so it can be reproduced anywhere.
    2. Define the services that make up your app in docker-compose.yml so they can be run together in an isolated environment.
    3. Run docker-compose up and Compose starts and runs your entire app.

#We Run One Application (Counter application on running) which include python and radis.
   # We have Following Commands to create and run the application using using Docker-compose.
       #mkdir composetest
       #cd composetest/
       #cat > app.py : copy the file given in this repository
       #cat > requirements.txt : Copy the file given in this repos.
       #vi Dockerfile  : copy the contains of Dockerfile
       #docker build -t myimg .
       #vi docker-compose.yml : Copy the code given in docker-compose.yml file & check which port is exposes.
       #docker-compose up : now up the yml file using this command  
       # Now go to browser and type http://<ip_address>:5000 
    
