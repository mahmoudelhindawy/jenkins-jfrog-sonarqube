# jenkins-jfrog-sonarqube
integrate jfrog artifactory and socnaraube woth jenkins in one pipline....

clone the repository 
move to the cloned directory
insure that docker and docker compose installed on your machine
run the command "sudo docker-compose -f docker-compose-jenkins-artifactory.yml up -d"
will end with three containers working together

1- http://localhost:8080/ --> jenkins container
2- http://localhost:9090/artifactory/webapp/home.html?2  --> jfrog artifactory
3- http://localhost:9000/about --> sonar qube
