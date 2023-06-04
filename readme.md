# Install Jenkins with Docker

```sh
docker run -v /var/run/docker.sock:/var/run/docker.sock -v $(which docker):$(which docker) -v `pwd`/data:/var/jenkins_home -v -p 8080:8080 --name jenkins-server -d jenkins/jenkins:lts-jdk11
```





