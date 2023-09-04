# Building the Docker Container

The code for the python app is found within the /src directory.

1. Run the appropriate Docker command to build the docker image.  Give the image a name of weather-app.

2. Run the appropriate Docker command to run a container with the newly built image and bind port 5000 on the container to port 5000 on your machine.

3. Verify the app works by navigating to http://localhost:5000

4. Stop weather app using docker 

> Side Note - If you are using M1/M2 MacOS and running into a 403 error try using port 5001 on your internal port number. 

# Docker Documentation

Here is a link to some docker comandline documentation to help.

https://docs.docker.com/engine/reference/run/


# Add Dockerhub Credentials to Jenkins

Before we build our pipeline, add your Dockerhub credentials to Jenkins.

To do this, navigate to the Jenkins dashboard and click "Manage Jenkins".

Then select "Manage Credentials"

Add your Dockerhub username and password.

These will be referenced in the pipeline we are about to build in the next excercises.

Here is a link to some Jenkins credentials documentation to help.

https://www.jenkins.io/doc/book/using/using-credentials/#adding-new-global-credentials