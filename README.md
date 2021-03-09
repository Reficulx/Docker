# Docker
This is a demo about building a docker python project from scratch. 

To Run This app through Docker on AWS Cloud9. 
First login to the AWS Cloud9 and create the computing environment. In the command line, login to your Docker using your username and passwork by entering `docker login` in the command line.  

Second, enter `docker pull reficulx/app` to pull the content into the cloud. Note: you could use `docker image ls` to check the images.  

Finally, enter `docker run -it reficulx/app bash` and `./app.py` to run the application file written by python.  
