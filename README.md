# SEPM-Prep

Preparation project for my university course in [Software Engineering and Projectmanagement](https://tiss.tuwien.ac.at/course/educationDetails.xhtml?dswid=2469&dsrid=61&courseNr=188909&semester=2021W&locale=en)

We will have to programm an application consisting of a database, an API Server and a web app. 
DISCLAIMER: 

- I am doing this as prep for myself
- I do not claim to be an expert, there is a possibility that I implement antipatterns
- This is not an official tutorial

## Project setup

- **Database:** H2
- **API Server:** [Java](https://openjdk.java.net/)
  - **Database Connectivity:** [Hibernate](http://hibernate.org/orm/)
  - **Server Framework:** [Spring Boot](https://spring.io/projects/spring-boot)
  - **Build Tool**: [Gradle](https://docs.gradle.org/current/userguide/userguide.html)
- **Frontend:** [Angular2](https://angular.io/)

I will use VSCode for Angular and IntelliJ for the API Server

I have no idea what version of those things is used in the course, I'll just use the newest versions currently available.

## What is the app

We'll keep it simple and small: A notes app
- Note consisting of header and text, and optionally a deadline
- Notebooks, grouping multiple notes together
- Tags, to search notes
- Maybe: users with passwords
