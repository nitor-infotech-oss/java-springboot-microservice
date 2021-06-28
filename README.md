# Microservices system using springboot

Microservices system using springboot provides implementations for microservices concepts
such as REST API, API gateway, Netflix Eureka service registry, Config Server, Zipkin, logger, Swagger UI. 

This repository provides common demo to show how the Microservices system using springboot
can be used. 

Table of Content:
--------------------------------------------------------------------------------
 1. [Overview](#1-overview)
 2. [Download](#2-download)
 3. [Requirements](#3-requirements)
 4. [Configure on a Local System](#4-configure-examples-on-a-local-system)
--------------------------------------------------------------------------------

## 1 Overview

	Microservices system using springboot

	1. Microservice​
		1. Product service​
		2. Store service​
	2. Eureka server​
		  Service registry ​
	3. ApiGateway​
		1. Pre Filter​
		2. Post filter​
		3. Route​
		4. Error​
		5. Authentication & Authorization​
	4. Swagger UI  for microservice​
	5. Config Server (using github)​
	6. Zipkin as monitoring​
	7. Logging 

## 2 Download

**Microservices system using springboot** can be downloaded as a [zip-file][download] (latest
'master' branch) or cloned with `git clone` from GitHub. GitHub offers HTTPS and SSH
as transfer protocols. See the [Download][wiki:download] wiki page for more details.

For SSH protocol use the URL `https://github.com/nitor-infotech-oss/java-springboot-microservice.git` or command
line instruction:


## 3 Requirements

**Microservices system using springboot** and the this repository come with 5 micoservices projects to ease most
of the common tasks, like rest api, monitor micoservices, logger, rest api flow tracing, common config etc.


##### Common requirements:

 - Programming languages and runtimes:
	- Spring Boot  2.2.x
 - Netflix Eureka service registry
 - zipkin
     - https://zipkin.io/
 - Swagger UI
     - https://swagger.io/tools/swagger-ui/	 
	 

## 4 Configure Microservices system on a Local System

To explore Microservices system's full potential, it's required to configure STS IDE.
Import all the project in STS.
How to run : We need to start project in following sequence :
	1. Config server.
	2. Registry server.
	3. Zipkin server.
		- How to start : https://zipkin.io/pages/quickstart.html
	4. Last product and store example rest api microservices.

