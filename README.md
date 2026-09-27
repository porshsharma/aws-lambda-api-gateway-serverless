# AWS Lambda + API Gateway Serverless Application

A serverless application built using AWS Lambda and Amazon API Gateway as part of my Cloud Computing Internship.

## Project Overview

The objective of this project was to create a serverless function using AWS Lambda and expose it through an HTTP API using Amazon API Gateway.

## Technologies Used

- AWS Lambda
- Python
- Amazon API Gateway
- AWS Management Console

## Architecture

Client
↓
API Gateway
↓
AWS Lambda
↓
JSON Response

## Workflow

1. Created an AWS Lambda function.
2. Implemented the function using Python.
3. Tested the Lambda function.
4. Created an API Gateway HTTP API.
5. Connected API Gateway with Lambda.
6. Deployed the API.
7. Tested the public API endpoint.

## Lambda Function

The function returns a JSON response containing a message, project name and status.

## Live API

https://rcv5x8yft.execute-api.ap-south-1.amazonaws.com/default/cloud-vm-serverless

## Sample Response

{
  "message": "Hello from AWS Lambda!",
  "project": "Serverless Function",
  "status": "success"
}

## What I Learned

- AWS Lambda
- Serverless architecture
- Python Lambda functions
- API Gateway
- HTTP APIs
- JSON responses
- Serverless deployment

## Screenshots

The project evidence collage contains screenshots of the Lambda function, successful test execution, API Gateway integration and the public API endpoint.

## Project Status

Completed
