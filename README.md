# Blog-Microservices-App

# ABOUT

Utilized React, NodeJS (Express), Docker, Kbernetes (Skaffold), HTML/CSS

This program allows users to post as well as view others posts. However, before a post is rendered it is filtered for any disturbing words. If such words are present then the post does not render, otherwise the post is rendered. Moreover, users also have the ability to comment on any certain post. This is a small project that leverages microservices architecture with the help of 5 back-end microservices and a React client app. Finally, docker was used mainly for building and deploying where as kubernetes took care of the managment of the docker containers (Skaffold set up for easy to use local k8s enviroments)

# Future Plans

I intend to enchance the UI of the current app as it is very minimalistic at the moment

# Installation

1- git clone repo<br>
2- Replace my docker id in all the .yml files with your own<br>
3- Skaffold dev<br>
