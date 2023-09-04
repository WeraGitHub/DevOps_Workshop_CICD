
# Push your image to Dockerhub

Add the appropriate step to your pipeline to login to Dockerhub using the credentials you stored in Jenkins.

Add the appropriate step to push the built image to Dockerhub.

Run your pipeline and verify that the image was pushed to Dockerhub.

# Deploy image from Image Registry (Dockerhub)

We can deploy the image now to different environments from a single repository.

Let's test this locally by running the appropriate command to pull the image from dockerhub.