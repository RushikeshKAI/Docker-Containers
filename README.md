# Docker-Containers
We covered below points
Docker Installation on linux systems, Docker Overview, Docker Basic Commands, Docker Hubs, Labs, Jenkins, Images, Entrypoint, Environment Variables, Docker-Compose, Docker Registry, Docker engine, Namespace-PID, Namespace, Storage and Networking, Container Orchestration, Swarm, Kubernetes, 


***Installation of Docker:***

Uninstall Older Versions:
> sudo apt-get remove docker docker-engine docker.io containerd runc


**Docker Installations:**

> curl -fsSL https://get.docker.com -o get-docker.sh
> DRY_RUN=1 sh ./get-docker.sh


Run Docker Virtually:

> sudo docker run docker/whalesay cowsay Hello Docker!



**Docker Commands:**

Command                                                 Description
docker ps	                                            List running containers
docker exec -it <container name> /bin/sh 	            SSH into container
docker restart <container name>	                        Restart a container
docker stats	                                        Show running container stats
docker system df	                                    Check docker daemon disk space usage
docker system prune -af	                                Remove images, networks, containers, and volumes



Important: How to Access the Labs
The Docker hands-on labs are hosted on KodeKloud. Use this link to register for the labs associated with this course.

You DON'T have to make any additional payment. Use the below coupon code to gain access to labs for free.
Coupon code: udemystudent1118

Link: https://udlabs.kodekloud.com/courses/udemy-labs-docker-for-the-absolute-beginner/



**Article on Jenkins Image**
This is an update for the Jenkins image.
I used a jenkins image which is now deprecated. Instead of that, we have to use jenkins/jenkins.
I used the command:-
> docker run jenkins
But as of now, we have to use the following command:-
> docker run jenkins/jenkins

Reference:-
https://www.jenkins.io/blog/2018/12/10/the-official-Docker-image/
https://hub.docker.com/r/jenkins/jenkins/


To stop all Containers:

> docker kill $(docker ps -q)


Labs - Docker Run
Access the labs here: https://udlabs.kodekloud.com/topic/labs-docker-run-commands-5/


Labs - Docker Images
Access the labs here: https://udlabs.kodekloud.com/topic/labs-docker-images-5/


Labs - Environment Variables
Access the labs here: https://udlabs.kodekloud.com/topic/labs-environment-variables-5/


Labs - Command vs Entrypoint
Access Labs here: https://udlabs.kodekloud.com/topic/labs-command-entrypoint-3/ ‎


Pre-Requisite - YAML
In this section you will need to work with YAML language. If you are not familiar with YAML enroll in this free course https://kodekloud.com/p/json-path-quiz


Labs: Docker Compose
Access Lab Here: https://udlabs.kodekloud.com/topic/labs-docker-compose-6/ ‎


References
Please click on the links below for further reference:
https://docs.docker.com/compose/
https://docs.docker.com/engine/reference/commandline/compose/
https://github.com/dockersamples/example-voting-app


Lab: Docker Registry
Access Lab Here: ‎https://udlabs.kodekloud.com/topic/lab-docker-registry-3/



Lab: Docker Registry
Access Lab Here: ‎https://udlabs.kodekloud.com/topic/lab-docker-registry-3/


Labs - Docker Storage
Access the labs here: https://udlabs.kodekloud.com/topic/labs-docker-storage-4/


Labs - Docker Networking
Access the labs here: https://udlabs.kodekloud.com/topic/labs-docker-networking-5/


How to Access the Labs:
The Docker hands-on labs are hosted on KodeKloud. Use this link to register for the labs associated with this course.
Use the below coupon code to gain access to labs for free.
Coupon code: udemystudent1118
Link: https://udlabs.kodekloud.com/courses/udemy-labs-docker-for-the-absolute-beginner/


# How to Run Vote-app

Run in this directory:

> docker-compose up

or either if you want to run it in background 

> docker-compose up -d

The app will be running at http://localhost:5000, and the results will be at http://localhost:5001.

