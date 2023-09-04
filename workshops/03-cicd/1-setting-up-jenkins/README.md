# Setting up Jenkins on macOS and Linux

Follow the instructions to download and run Jenkins in a Docker Container.

https://www.jenkins.io/doc/book/installing/docker/#downloading-and-running-jenkins-in-docker

It is improtant to note that before running your custom myjenkins-blueocean container, think about how you would allow Jenkins to be able to access this workshop repository. This is necessary for Jenkins to be able to use the files in the directories later.

# Post Installation Setup Wizard

Once the Docker container is running, follow the post-installation setup wizard to unlock and do an initial setup for Jenkins.

https://www.jenkins.io/doc/book/installing/docker/#setup-wizard

## Hint

To unlock Jenkins look at the container logs for the initial password by using the appropriate docker commands.

Install all the suggested plugins.