# springboot-azure-functions
Spring boot app that integrates with Azure's Cosmo DB and deploys an Azure Functions with an HTTP Trigger.

# Quick Start

```gradle jar --info```

```gradle azureFunctionsRun```

```curl http://localhost:7071/api/HttpTrigger-Java -d "{\"name\":\"Val\"}"```

```az login```: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-macos?view=azure-cli-latest

```gradle azureFunctionsDeploy```

```curl https://varena-function1.azurewebsites.net/api/HttpTrigger-Java -d "{\"name\":\"Azure\"}"```


