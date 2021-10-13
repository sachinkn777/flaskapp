# flaskapp

Steps to build and run custom docker container:
1. Pull the repository:
    git clone "https://github.com/sachinkn777/flaskapp.git"

 2.Move to flaskapp folder and build the docker file as below:
    docker build -t myflask:v1 .

 3.Run the docker image to create a container and test the application:
      docker run -d -p 5000:5000 myflask:v1
      
 4.check the logs of the dcoker container created:
    docker logs container_id
    
 5.Open browser and type http://localhost:5000    
