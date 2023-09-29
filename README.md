# Docker-practice
It contains all the practice docker file and images


STEPS FOR APACHESERVER
=========================
1-Create docker file.
2-Create index.html on host machine
3-Build image 
4-Run container with exposed port



😍you pull image from docker hub by usning this name "naveen20/apachewebserver"

docker pull naveen20/apachewebserver


![image](https://github.com/naveen201/Docker-practice/assets/42841119/eec56c4f-aa65-4198-ba95-bb48c871d75d)




===============================History

   16  vi index.html
   17  docker build -t apacheimage .
   18  docker images
   19  docker run -td -name apache2 -P apache2server
   20  docker run -td --name apache2 -P apache2server
   21  docker ps
   22  docker images
   23  docker login
   24  docker tag apacheimage naveen20/apachewebserver
   25  docker images
   26  docker push naveen20/apachewebserver
   27  ll
   28  cat Dockerfile
   29  cat index.html
   30  history





