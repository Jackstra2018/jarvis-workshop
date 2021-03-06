# Alexa, Ask Jarvis to Create a Serverless App for Me

Ever dreamed making a voice assitant capable of helping you out in your work as a developer? Or a voice assistant that would be able to develop quick prototypes or even complete applications?

Well, even if you haven't dreamt, this workshop will help you unleash the whole power of AWS to help you out in your everyday work!

## Contents

This workshop is team based. Each team has a goal of building their own serverless voice assistant and completing as much as possible.

The workshop is organized into several task sections:

- Alexa Skill (in the [`/1-alexa-skill`](/1-alexa-skill))
- Application Repository (in the [`/2-app-repo`](/2-app-repo))
- Comprehend (in the [`/3-comprehend`](/3-comprehend))
- DynamoDB (in the [`/4-dynamodb`](/4-dynamodb))
- Connect It all (in the [`/5-connect-it-all`](/5-connect-it-all))

The minimum is to complete the Alexa Skill, Application Repository, Comprehend.

### 1 Alexa Skill Tasks

These tasks are focused on building the necessary Alexa skill intents that are going to be the your interface to create applications and their services.

**Difficulty**: *Medium*

You can find more details in the [/1-alexa-skill](/1-alexa-skill) folder.

### 2 Application Repository Tasks

Application Repository tasks are focused on creating methods to interact with the AWS API for the Serverless Application Repository and CloudFormation, to search serverless components, get each one and deploy them using CloudFormation.

**Difficulty**: *Easy*

You can find more details in the [/2-app-repo](/2-app-repo) folder.

### 3 Comprehend Tasks

Comprehend tasks are the core of your application. They are focused on creating methods to interact with the AWS API for the Comprehend and to do further custom analysis and combinations needed for detecting which serverless components to use.

**Difficulty**: *Hard*

*Hint*: *If possible, develop it in a pair-programming fashion*

You can find more details in the [/3-comprehend](/3-comprehend) folder.

### 4 DynamoDB Tasks (Optional)

These tasks are focused on storing the created application and their corresponding services information to their DynamoDB tables for further work. These tasks should build methods for saving and getting created application information and saving and getting created service information (such as name, appId, input, process, output) which are interacting with the AWS API for DynamoDB.

**Difficulty**: *Easy*

You can find more details in the [/4-dynamodb](/4-dynamodb) folder.

### 5 Final task: connect all services together

At this point, your team will need to connect all services you built.

You can find more details in the [/5-connect-it-all](/5-connect-it-all) folder.

**Difficulty**: *Medium*

## Useful links

- [Handling Requests sent by Alexa](https://developer.amazon.com/docs/custom-skills/handle-requests-sent-by-alexa.html)
- [Comprehend SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/Comprehend.html)
- [Serverless Application Repository SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/ServerlessApplicationRepository.html)
- [DynamoDB SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/DynamoDB.html)

(c) Copyright 2018 Aleksandar Simovic, All Rights Reserved.