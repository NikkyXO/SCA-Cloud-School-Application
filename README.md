# SCA-Cloud-School-Application

Created a Dockerfile with Nodejs
Ran the project locally

  Testing the Node Application

    Navigate into the docker folder
    Run npm install && npm start
    Go to http://localhost:8081 to view designated text "Welcome to Cloud school Application"

Run Docker Image Start Branch

    Navigated into the root folder
    built Docker image - Type docker build -t dockerstart .
    Ran the Docker image - docker run -p 49160:8081 -d dockerstart
    On Docker desktop, click "view in browser" to view the designated welcome message.

Run Docker Image Feature Branch

    Checkout to feature branch.
    Built Docker image - Type docker build -t docker-feature .
    Ran the Docker image - docker run -p 4990:8080 -d docker-feature
    Click "view in browser" in Docker desktop, you should have the welcome message. "Welcome to SCA Cloud School Application , this is my first assessment"

View Docker images and id

    Run docker images

Push to docker repo

    Created a repo in docker hub, my repo
    Run docker tag image-id:yourhubusername/reponame:tag
    Run docker push yourhubusername/reponame:tag
    Did same for feature branch in the same repo

Docker Hub Repo [DockerHub]
(https://hub.docker.com/repository/docker/nikkydr/sca-cloud-school-application)
