# Docker


1. Tagging a docker image before pushing to dokcer hub repo:
  docker tag nginx:latest cvan26/myrepo:nginx1
2. List image:
   docker image ls
3. List container 
   docker ps -a
4. Run container and map port
   docker run -d -p 8080:80 --name nginx nginx:latest

6. pull nginx image to repo on dockerhub:
![dockerlabrepo](https://github.com/Cvan26/Docker/assets/120164151/bca7916a-0bad-44f2-a3b7-a1ed5b994573)


