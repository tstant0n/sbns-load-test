# Azure Service Bus Deployment

This repository contains an ARM template for deploying an Azure Service Bus namespace with a predefined configuration. It's designed to streamline the setup process for a Service Bus namespace and a queue, allowing for quick deployment to Azure.

## Features

- **Service Bus Namespace**: Configures a namespace in Azure Service Bus.
- **Queue**: Creates a queue within the Service Bus namespace with default settings.

## Prerequisites

Before you begin, ensure you have an active Azure subscription. If you do not have one, you can create a free account at [Azure Free Trial](https://azure.com/free).

## Deploy to Azure

Click the button below to deploy the Service Bus namespace and queue to your Azure subscription:

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Ftstant0n%2Fsbns-load-test%2Fblob%2Fdev%2Ftstanton%2Fclick-to-deploy%2Fdeploy-servicebus.json)

## Deployment Steps

1. Click the "Deploy to Azure" button.
2. Sign in to the Azure Portal if prompted.
3. Fill in the required fields on the Custom deployment page:
   - **Subscription**: Choose the subscription to deploy the resources.
   - **Resource Group**: Select an existing resource group or create a new one.
   - **Location**: Select the location for your resources.
   - Fill in any other parameters as needed.
4. Review the terms and conditions, then click "I agree to the terms and conditions stated above".
5. Click "Purchase" to start the deployment. (Note: There is no actual purchase necessary for deploying free or already included services in your subscription).

## Post-Deployment Configuration

After deployment, you may want to configure additional settings for the Service Bus namespace or queue through the Azure Portal or Azure CLI.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes or improvements.
