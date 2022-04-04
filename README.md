# SCA-Cloud-School-Application

Created a Dockerfile with Nodejs

Running the project locally

    Fork this repository
    Clone to your local machine and navigate into the repository.
    Checkout to the branch Start from main branch

Testing the Node Application

    Navigate into the docker folder
    Run npm install && npm start
    Go to http://localhost:8080 to view welcome message

Run Docker Image Start Branch

    Navigate into the root folder
    To build Docker image - Type docker build -t dockerstart .
    To run the Docker image - docker run -p 49160:8080 -d dockerstart
    On Docker desktop, click "view in browser" to view the welcome message.

Run Docker Image Feature Branch

    Checkout to feature branch.
    Build Docker image - Type docker build -t docker-feature .
    Run the Docker image - docker run -p 4990:8080 -d docker-feature
    Click "view in browser" in Docker desktop, you should have the welcome message. "Welcome to SCA Cloud School Application , this is my first assessment"

View Docker images and id

    Run docker images

Push to docker repo

    Create a repo in docker hub, my repo
    Run docker tag image-id:yourhubusername/reponame:tag
    Run docker push yourhubusername/reponame:tag
    Did same for feature branch in the same repo

Docker Hub Repo
