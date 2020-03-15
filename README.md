# springboot-azure-functions
Spring boot app that integrates with Azure's Cosmo DB and deploys an Azure Functions with an HTTP Trigger.

# Azure Functions: Types of Triggers
* HTTP Trigger - This trigger gets fired when the HTTP request comes.
* Timer Trigger - This trigger is called on a predefined schedule.
* Blob Trigger - This trigger will get fired when a new or updated blob is detected.
* Event Hub Trigger - This trigger will get fired when any events are delivered to an Azure Event Hub.
* Queue Trigger - This trigger gets fired when the Webhook HTTP requests come from any service that supports Webhooks.
+ GitHub Webhook - This trigger is fired when an event occurs in your GitHub repositories.
* Service Bus Trigger - This trigger is fired when a new message comes from a service bus queue or topic.

# Quick Start

```gradle jar --info```

```gradle azureFunctionsRun```

```curl http://localhost:7071/api/HttpTrigger-Java -d "{\"name\":\"Val\"}"```

```az login```: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest

```gradle azureFunctionsDeploy```

```curl https://varena-function1.azurewebsites.net/api/HttpTrigger-Java -d "{\"name\":\"Azure\"}"```


