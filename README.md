# SCA-Cloud-School-Application
Application for SCA cloud school
## SUBMISSION OF EXERCISE 1

### This is a readme file for describing my processes used for:
* Creating and cloning my repository `SCA-Cloud-Application-School` from github using:
`git clone https://github.com/cornelia247/SCA-Cloud-School-Application.git`
* Creating my `HTML` file and `Dockerfile` using commands like `FROM`, `RUN` and `COPY` for my webpage that displays ___"Welcome to SCA Cloud School Application"___ 
* Built the Image container using `docker build -t cornelia247/sca-cloud-school:v1 .`
* Ran the Image at `localhost:3000` using `docker run -p 3000:80 cornelia247\sca-cloud-school:v1`

#### Deployment
* Tagged my docker image using `docker tag efc097705710 cornelia247/sca-cloud-school-application-docker:commitsca`
* Pushed into Docker hub using `docker push cornelia247/sca-cloud-school-application-docker:commitsca`

## DOCKERHUB LINK
* [Docker hub Repository](https://hub.docker.com/repository/docker/cornelia247/sca-cloud-school-application-docker)



