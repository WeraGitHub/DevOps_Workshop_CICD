# Building your first Pipeline

1. Start by creating your first pipeline. To do this select + New Item from the left hand menu and give the pipeline a name such as build-weather-app.

2. Select the Pipeline option and click ok.

3. Give your pipeline a Description and build your Pipeline script with the following template as a good starting point: (Do not tick any other options)

pipeline {
    agent any

    stages {
        stage('') {
            steps {
                script {
                   
                }
            }
        }
    }
}


4. Give the pipeline stage a name of 'Access Volume Mount'

5. Research and add steps to your script to list out the files in the workshop directory and make a note of which directory your job runs from.*

6. Click save and apply when you have added your steps.

7. Press Build Now to run your pipeline

8. Press Configure to change your pipeline Script.

*NOTE if you did not follow the hint in 1-setting-up-jenkins, you may want to revisit and retry.


# Create your build Pipeline

Add a stage to your pipeline to build the docker image with similar commands to what you used locally.

Congratulations you have created an image using a pipeline
