# Dockerbasics

Running selenium program from docker

Step1 : 
Install selenium/standalone-chrome from 
https://hub.docker.com/r/selenium/standalone-chrome
command: docker pull selenium/standalone-chrome



Step 2 : 
docker run -d -p 4444:4444 -v /dev/shm:/dev/shm selenium/standalone-chrome:latest



