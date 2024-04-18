
# Project Title

To deploy a pre-made full stack application using docker file and docker compose. 


## Deployment

To deploy this project one has to make two docker files . One for frontend and one for the backend.
 to run our compose file :
 docker-compose up --build
also we might need to include java enviornment variables in our compose file so we don't have to change in jar file once made.


## Documentation

This project is all about deploying a premade application.
The application:https://github.com/luuvantuan1992/ReactJS-Spring-Boot-CRUD-Full-Stack-App-master

we have prepared dockerfiles and compose file for this project to be deployed.

This is a full stack application.So we can face certain issues while deploying these type of applications.
I mm writing some of the issues i faced due to which it took a bit more time .
1. while making the compose file we need to link database to the backend.
2. also there can be issue in port mapping.
3.the enviornment variable file of java mmust be kept into consideration as we might need to change them acc to our database.


