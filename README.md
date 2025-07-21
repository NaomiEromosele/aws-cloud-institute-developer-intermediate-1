# aws-cloud-institute-developer-intermediate-1
The capstone course repository. Contains all labs for the customer onboarding application, demonstrating microservices, serverless architecture, and event-driven patterns.
---

## Course Description
This course focuses on deploying microservices for event-driven applications on containers or in a serverless fashion. The central part of this course is a capstone project to design and develop a working application using AWS services and Python.

---

## Key Skills & Concepts Learned
- Web development fundamentals with HTML, CSS, and JavaScript.
- Building full-stack web applications using the Django framework with Python.
- Decomposing monolithic applications into a microservice architecture.
- Designing and building serverless applications with AWS Lambda, API Gateway, and DynamoDB.
- Implementing event-driven patterns using Amazon SQS, SNS, and Step Functions.
- Deploying serverless applications efficiently using the AWS Serverless Application Model (AWS SAM).
- Integrating AWS AI services like Amazon Rekognition and Amazon Textract into an application workflow.

---

## Capstone Project: Customer Onboarding Application
This repository contains the full source code and infrastructure definitions for the capstone project.

* **Description:** Developed a serverless, event-driven application to automate a customer onboarding process. The application accepts customer documents via an S3 bucket, uses Lambda functions to process the data, leverages Amazon Rekognition and Textract to validate identity, stores results in DynamoDB, and uses Step Functions to orchestrate the workflow.
* **Architecture:** The application is built on a microservices architecture using AWS Lambda, API Gateway, S3, SQS, SNS, DynamoDB, and Step Functions. It is deployed using the AWS Serverless Application Model (SAM).
* **Source Code:** `./capstone-project`
