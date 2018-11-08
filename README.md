# Survival-Game
Unity 3d Survival Game

This game is build in Unity 3D to play this game Downlaod these files and open index.html

You can also run this in docker, just follow steps shown below.

1- Create a docker file dockerfile 
2 - Write this in docker file
FROM nginx:latest
ADD Survival-Game-master /usr/share/nginx/html
EXPOSE 80

3- Build docker image
docker build -t SurvivalGame. 

4- run docker
docker run -d -p 80:80 SurvivalGame

5- open game in browser
127.0.0.1:8080/index.html
