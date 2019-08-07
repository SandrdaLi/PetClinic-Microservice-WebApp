## Hands on tutorial: AWS Elastic Compute Containers

## Objective:
### 1. Understand Virtual computing environments, known as instances.
### 2. Set up various configurations of CPU, memory, storage, and networking capacity for your instances.
### 3. Achieve knowledge on Persistent storage volumes for your data using Amazon Elastic Block Store (Amazon EBS)
### 4. Experience on implementing Scalable Microservice architecture.

## Introduction
### Java Microservices Deployed on EC2 Container Service
This is a reference architecture that shows the evolution of a Java application from a monolithic application that is deployed directly onto instances with no containerization or orchestration, to a containerized microservices architecture orchestrated using Amazon EC2 Container Service.

We will take the [Spring Pet Clinic](https://github.com/spring-projects/spring-petclinic) as the base to extend from.
A high level architecture of PetClinic app is as follows,
![alt text](https://github.com/awslabs/amazon-ecs-java-microservices/blob/master/images/PetClinicApp.png)

So lets get to it,
1. [Part One: Moving existing Java Spring application to a container deployed using ECS](https://github.com/awslabs/aws-java-microservice-refarch/blob/master/1_ECS_Java_Spring_PetClinic)
2. [Part Two: Breaking the monolith apart into microservices on ECS](https://github.com/awslabs/aws-java-microservice-refarch/tree/master/2_ECS_Java_Spring_PetClinic_Microservices)
3. [Part Three: Create a continuous integration and continuous delivery](https://github.com/awslabs/aws-java-microservice-refarch/tree/master/3_ECS_Java_Spring_PetClinic_CICD)

## Prerequisites

You will need to have the latest version of the AWS CLI and maven installed before running the deployment script.  If you need help installing either of these components, please follow the links below:

1. [Installing the AWS CLI](http://docs.aws.amazon.com/cli/latest/userguide/installing.html)
2. [Installing Maven](https://maven.apache.org/install.html)
3. [Installing Docker](https://docs.docker.com/engine/installation/)
4. [Installing Python](https://www.python.org/downloads/)
5. [Installing JQ](https://stedolan.github.io/jq/download/)
