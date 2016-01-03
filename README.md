# Jenkins Workflow Docker
A docker image which contains a Jenkins server that has the docker tools and the workflow plug-ins installed.

The `Dockerfile` inherits form the official `jenkins` base image, installs the Docker tools and downloads all the plugins defined in `plugins.txt`.

## How to run
You can use the same options as described in the official Jenkins image: https://hub.docker.com/_/jenkins

## Example
I used this in a [sample](https://github.com/MicroserviceWorkshop/JenkinsWorkflowDockerSample) with a more complex Jenkinsfile. 
