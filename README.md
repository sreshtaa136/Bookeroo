# RMIT SEPT 2021 Major Project

# Group Day-Time

## Members
Shanil Gunawardane
Anne Maria Sunil
Sai Sreshtaa Turaga

## Records

* Github repository :https://github.com/s3805922/SEPT_Team3
* jira Board : https://sept-group3.atlassian.net/jira/software/projects/ST/boards/1/backlog

Application not dockerised or added to circle ci. Will be done for next sprint 

To run the application locally :
1. checkout to branch 'dockerise'
2. cd into loginmicroservices and run :
  ./mvnw package && java -jar target/loginmicroservices-0.0.1.jar
3. cd into bookmicroservices and run :
  ./mvnw package && java -jar target/bookmicroservices-0.0.1.jar
4. cd into FrontEnd/myfirstapp
5. run "npm install"
6. run "npm start"
