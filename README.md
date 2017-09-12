# Fork of the official Jenkins Docker image that uses Ubuntu trusty as base
# and adding docker inside and cmake and g++
## to run it:
docker run -d -v /var/run/docker.sock:/var/run/docker.sock \
              -v /path/to/your/jenkins/home:/var/jenkins_home \
              -p 8080:8080 \
              aharonamir/jenkins-ubuntu-docker
              
