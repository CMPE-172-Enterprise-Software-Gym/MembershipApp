# Gym Membership Web App

## Authors
San Jose State University
Course: EnterpriseSoftware-CMPE172/Spring2020
Team Members: Gerardo Garcia, Benny Ooi, Trevor O'Neil

## Project Description
Gym Membership app is a subscription service web application that is connected to the AWS cloud.

## UI Demo Screenshots
https://github.com/CMPE-172-Enterprise-Software-Gym/MembershipApp/issues/2#issue-613031081

## Pre-requisites:
MySql workbench
Springboot
AWS account
Docker
Eclipse
AWS Toolkit for Eclipse


## Installation
Download the zip file and import onto Eclipse. On AWS create an RDS database instance. Use your RDS endpoint url to connect to MySql. Next, open up the Springboot application locally and on the application properties file, include your RDS endpoint url, and your MySql credentials as well. After including that information on the application properties file, you can deploy the Springboot application on your localhost server. The Springboot application will now be connected to your MySql and your RDS instance as well. Once you have ensured connection, launch an AWS EC2 instance. On Eclipse, using the AWS Toolkit, connect to your EC2 instance by providing the required credentials information including your key-pair. Finally, create a new Elastic Beanstalk environment on AWS so we can deploy our Eclipse project. Once the Elastic Beanstalk environment is up and running, export a WAR file from the Eclipse project and upload it to the Elastic BeanStalk Environment. The application should now be available to view by clicking on the web app url given on AWS.

## Schema and REST API screenshot
https://github.com/CMPE-172-Enterprise-Software-Gym/MembershipApp/issues/1#issue-613028601




	
