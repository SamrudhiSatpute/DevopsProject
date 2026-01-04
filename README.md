# DevopsProject

#jenkins using docker 

first pull the image and make a container of jenkins for port 8081
docker run -d \
  --name jenkins \
  -p 8081:8080 \
  -p 50000:50000 \
  -v jenkins_home:/var/jenkins_home \
  -v /var/run/docker.sock:/var/run/docker.sock \
  jenkins/jenkins:lts

then get the password login 

Making pipeline GitHub Repo → Jenkins Pipeline → Build → Success
getting the plugins required
