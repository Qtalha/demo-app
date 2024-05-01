hello world

# Created the CI/CD pipeline with Github Actions .

## First created the Demo-app repository for the static web page and pushed the index.html file to the remote repository .

## Then through Github actions I have created a workflow in which the pipeline is written on YAML format .

## I have used the AWS EC2 for Deploying the application code . And the docker container is also deployed on that.

## For connecting the Self-hosted runner to the Github Actions i have followed the steps suggested by them and thus connected the Self-hosted runner (EC2 server) to the actions.

## The condition there is used as per the doc i.e build after every push to the main branch .

## I have tested the same by pushing the 2 commits to the remote repository and that can be seen in the build section.





