# Overview

[![Python application test with Github Actions](https://github.com/sahil8060/Building-a-CICD-Pipeline/actions/workflows/pythonapp.yml/badge.svg)](https://github.com/sahil8060/Building-a-CICD-Pipeline/actions/workflows/pythonapp.yml)

## Overview of the project

This project is build to demonsrate the skills learned throught the Udacity course **Agile Development with Azure** from **Cloud DevOps using Microsoft Azure Nanodegree Program**. In this project we had build the project plan make the Trello board for the DevOps team to follow. Then we provide **Continuous Integration** and **Continuous Delivery using Azure Pipeline** for python application.

## Project Plan

* A [Udacity Project](https://trello.com/b/B40CyvxR) to a Trello board for the project. Also you can scan QR code

![trello-board-qr-code](trello-board-qr-code.png)

* A link to a spreadsheet that includes the original and final project plan>

## Instructions

* Architectural Diagram (Shows how key parts of the system work)>

![cd-diagram](cd-diagram.png)

Instructions for running the Python project.

* Project running on Azure App Service

![App_Service_UI](screenshots/App_Service_UI.png)

* Project cloned into Azure Cloud Shell

![Github_Clone](screenshots/Github_Clone.png)

* Passing tests that are displayed after running the `make all` command from the `Makefile`

* Output of a test run

![Make_all_test_pass](screenshots/Make_all_test_pass.png)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).


![Pipeline_Success](screenshots/Pipeline_Success.png)

* Running Azure App Service from Azure Pipelines automatic deployment

![Pipline_Jobs_In_Run](screenshots/Pipline_Jobs_In_Run.png)

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/sahil8060/Building-a-CICD-Pipeline/blob/main/make_predict_azure_app.sh).
The output should look similar to this:

![Make_Predict](screenshots/Make_Predict.png)


* Successful prediction from deployed flask when you run app Locally.  [Use this file as a template for the deployed prediction](https://github.com/sahil8060/Building-a-CICD-Pipeline/blob/main/make_prediction.sh).
The output should look similar to this:

![Make_Predction_App](screenshots/Make_Predction_App.png)

* Output of streamed log files from deployed application

![Web_App_CLI_Logs](screenshots/Web_App_CLI_Logs.png)

![Make_all_test_pass](screenshots/Make_all_test_pass.png)

## Enhancements

<TODO: A short description of how to improve the project in the future>
Intially we are working with single github repositry in the future we will create three branches. As we had learned about three major environments of project building.
1. Testing
2. Staging
3. Production

Once we completed the testing and staging phase successfully then we will push the codes to the production respository.

## Demo 

[youtube](www.youtube.com)


