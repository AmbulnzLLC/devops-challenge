# Devops Challenge for Candidates

In order to assess a candidate's ability to perform hands-on devops tasks, we provide the following exercise. It's expected to take about one hour. Candidates are welcome to use Google, StackOverflow, and any other resources that will help them in this process and to ask questions of the interviewer.

If the candidate wishes to use their own computer, they're welcome to. Otherwise, one will be provided. The main work will be executed on an Amazon EC2 instance via SSH. The instance will be provisioned with the following tools:

* Nodejs
* Docker & docker-compose
* Git
* The AWS command-line tool configured with sufficient credentials to complete the task.

## The exercise

A consultant engineer was in the middle of setting up a Jenkins server on an AWS instance when his contract ended. You have the name of the instance (devops-challenge,) the SSH key (candidate-unsafe,) and very little else.

Shell into the EC2 instance, examine the running containers and the code in this repository. Troubleshoot why the Jenkins web UI isn't working and possible solutions. If you make any changes to this repository, make them in a branch and push them to github.

On the EC2 instance, the code is in /code/devops-challenge.
