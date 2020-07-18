# Practical Test
> This is a hands-on practical test design to challenge participants on their debugging skills.  

**As a wise man once said, a good developer is a better debugger. **

## Introduction 
This is a simple TaskManager application built using `NestJS`, `Postgres` and `React`. The project is using `Nginx` as a proxy service. 
In the root of the project you can find `server`, `client`  and the `nginx` configuration folder. 


## 1. Booting up 
	1. Please clone the following repository inside `~/workspace/team9/`
	https://github.com/maminio/practical-test.git
	2. Create and checkout a branch with your first name and date id: 2020/12/25 => 20201225
	3. Build the project by using `docker`  and  `docker-compose`  
	4. Start up the docker-compose and keep the log stream open.
	5. The WebApp should be accessible from `http://team9.local`


## 2. Signup Debug
> As you can see the Web-app is not able to create new account and whenever you click on signup it navigates back to login.  

	1. Find the problem from the client side and explain why this is happening
	2. Checkout the out going calls from the client side and try fixing it further. 


## 3. Create Delete All Tasks functionality 
Create a `Delete` functionality which removes all tasks of a user and returns all of the tasks in the form of Array of objects.


## 4. Docker Compose Networking 
In a normal docker-compose, networking between services is managed automatically and service can access each other without any restriction. Please update the `docker-compose.yaml` file so that only the `api` service has access to `postgres` and not the `app` service. 

## Submission 
	* Make sure your code has no lint errors 
	* Make sure your code has no build or runtime error
	* Make sure you do not push any non-required files to the repository
	* Your source code must have comments and readable (Don’t overkill it tho!)

## Extra Challenges 
	1. Create a worker service and separate the `auth` service from the `api`  service. 






