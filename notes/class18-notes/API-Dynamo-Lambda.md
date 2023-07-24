# AWS: API, Dynamo and Lambda

## AWS API Gateway Overview

What is Amazon API Gateway?
>It's a service provided by Amazon that almost like replaces the conventional REST API servers backend, and allow to define your routes and link them with the needed logic on Amazon gateway, basically handling HTTP requests.

Why is Amazon API Gateway an important part of the Serverless ecosystem?

>it's like the link between the functions of Lambda and a functionless API server, to link them together to get a fully functionining serverless API.

How does API Gateway integrate with other AWS services?
>it integrated with other services such as Lambda, SNS, IAM and Cognito Identity Pools. allowing for managing and preparing authentication - authorization layers for such APIs (especially for Cognito)

>For Lambda it take benefit of function writing and make these functions run on the defined endpoints.
While for SNS (Simple notification service) it allows notifications for the accessed API endpoint.

## AWS API Gateway

>What are the some benefits of using Amazon API Gateway?
the most important benefit, is you got covered with good servers provided by amazon, which can handle any overload in terms of throttling, security, monitoring and Traffic, also it provides you a free 1 million API call every month for 12 month free trial. so you can test it.

What two API types might you choose from?

1. RESTful API
2. Websocket API

## AWS DynamoDB Guide

What is DynamoDB?
>a NoSQL database that amazon offers, it has the common NoSQL benefits of supporting scalable applications.

Under what circumstances would you recommend DynamoDB over MongoDB?
>If you are using serverless API functionalities then Dynamo would give you the most suitable options because it's integrated over AWS serverless services.

AWS DynamoDB

Explain to a non-technical friend how DynamoDB works.

>Imagine you have much of items all are similar types, like for example books, what way would you use to store it so it won't be in danger of spoiling and how to access the book you want to read as fast as possible?, DynamoDB is like that super Library, it provides you that cabinet (of books) to store books in and label each book with (key) that you just use to take that book out of the cabinet, and it has already multi(workers) who would keep your books safe (serverless AWS serviceses).

## Dynamoose

What is Dynamoose?
>A modelling tool for Amazon Dynamo, let's say to make it familiar it's like Mongoose for MongoDB and like Sequelize for PostgreSQl.providing easier syntax and much of build in methods to shortcut functionalities.

What are some key features of Dynamoose?

1. Type safety
2. High level API
3. Easy to use syntax
4. DynamoDB Single Table Design Support
5. Ability to transform data before saving or retrieving items
6. Strict data modeling (validation, required attributes, and more)
7. Support for DynamoDB Transactions
8. Powerful Conditional/Filtering Support
9. Callback & Promise support
10. AWS Multi-region support

## Things I want to know more about

Learn using the new NoSQL database (Dynamo) side by side with Lambda functions to build an API functioning as the conventional ones.