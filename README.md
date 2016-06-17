# docker

build iamge:
docker build -t alex/jenkins:2 .

run image:
docker run -p 8080:8080 -p 50000:50000 -v ~/dev/jenkins:/var/jenkins_home alex/jenkins:2

