# Overview
In this project, I will demo building a CI/CD Pipeline to Azure App Service:
* Deploy the app in Azure CloudShell
* Deploy the app as a web server using Azure App Service
 
## Project Plan


* A link to a [Trello board](https://trello.com/b/AkYzyi7B/azureproject2) for the project
* A link to a spreadsheet that includes the original and final project plan

## Instructions 
* Architectural Diagram
 ![diagram](https://github.com/Nguyen-XuanLInh/Udacity_Azure_Project2/blob/main/Screenshots/diagram.png)

* Project running on Azure App Service

* Project cloned into Azure Cloud Shell
  ![gitClone](https://github.com/Nguyen-XuanLInh/Udacity_Azure_Project2/blob/main/Screenshots/gitClone.jpg)
* Passing tests that are displayed after running the `make all` command from the `Makefile`
  ![makeAll](https://github.com/Nguyen-XuanLInh/Udacity_Azure_Project2/blob/main/Screenshots/makeAll.jpg)
* Output of a test run

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application
  ![log1](https://github.com/Nguyen-XuanLInh/Udacity_Azure_Project2/blob/main/Screenshots/Log1.jpg)
  ![log2](https://github.com/Nguyen-XuanLInh/Udacity_Azure_Project2/blob/main/Screenshots/Log2.jpg)

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


