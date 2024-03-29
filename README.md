# FreeBSD Maven Project - How to create a Java web application project With FreeBSD
Maven 3.9.6, JUnit 5, Logback, Spring 5 MVC and Jetty web server. A simple web project to display a current date.

You can read the complete article at - https://www.unixwinbsd.site/2024/01/build-java-app-with-maven-on-freebsd.html


## 1. How to run this project?

### 1.1 Test it with Jetty web server.
```
$ git@github.com:unixwinbsd/blogapp_project.git
$ cd blogapp_project
$ mvn compile && mvn package && mvn install 
$ mvn jetty:run
```
Access http://localhost:8080


### 1.2 Create a WAR file for deployment :
```
$ git@github.com:unixwinbsd/blogapp_project.git
$ cd blogapp_project
$ mvn compile && mvn package && mvn install 
$ mvn war:war
```
A WAR is generated at 'target/finalName'# blogapp_project
# Project Java With Maven On FreeBSD
