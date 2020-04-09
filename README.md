Table of Contents
=================
<!--ts-->
 * [Introduction](#introduction-to-assault-training-project)
 * [Installation](#installation)
    * [Requirements](#requirements)
    * [Running the application locally](#running-the-application-locally)
    * [Packages](#packages) 

## Introduction to Assault Training Project
Project for Officers training in Assault cases, this application will help the officers to undergo an interactive online training and further the application has quizzes to test the knowledge of the individual after the training.

## Installation

### Requirements
Following are the prerequisites to deploy the application on local system:
1. Java - JDK 1.8
2. Maven 4.0
3. MySQL DB
4. Apache Tomcat Server

### Running the application locally
There are 2 ways to run Spring boot application locally:
1.	Execute the `main ()` method in the `AssaultTrainingApplication.java` class in com.uga.socialworkdept package
2.	Use the Spring Boot Maven plugin like: `mvn spring-boot:run`

### Packages
1.	com.uga.socialworkdept – Includes the main method file to run the Spring boot application.
2.	com.uga.socialworkdept.controller – Includes files defined to listen to the client
3.	com.uga.socialworkdept.helper – Includes Java constant files and Password Authenticator file
4.	com.uga.socialworkdept.model – Includes files to hold entities
5.	com.uga.socialworkdept.repository – Files required to communicate with the database
6.	com.uga.socialworkdept.service – Files required to hold business logic
7.	src/main/resources/static – Contains static resources as css, js, images and sql as subfolders
8.	src/main/resources/templates – Contains server-side templates which are rendered by Spring i.e the HTML files
9.	src/main/resources/application.properties – This file includes application-wide properties such as server’s default port, server’s context path, database URLs, etc.
10.	src/test/java - Includes files required for unit and integration testing 
11.	pom.xml – This file includes all project dependencies
