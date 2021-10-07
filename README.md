# Azure Analytics Accelerator

The following accelerator can be used to deploy `Azure Purview`, and `Azure Key Vault` into an Azure Resource Group.  It will allow you to explore some of the Data Governance capabilities available on Microsoft Azure.  

## Purpose

The purpose of this Analytics Accelerator is to help you learn and grow through Hands-on common use cases that show you how to use Azure Purview.

This [GitHub Repository](https://github.com/DataSnowman/purviewARM) along with an Azure Subscription [No Azure Subscription click here](https://azure.microsoft.com/en-us/free/) should allow you to accelerate:

* Business Value
* Time-to-insight
* Modernization
* Skilling
* Proof of Concepts
* Architecture choice
* Infrastructure as code for PoC, Dev, Test, Prod

## Use Case

| Deployment | Use Case Name | Use Case Type | Dataset | Description | Code | Instruction Steps |
| :------------- | :----------: | :----------: | :----------: | :----------: | :----------: | :----------: |
| [Azure Purview](https://github.com/DataSnowman/purviewARM#deploy-azure-purview) | Data Governance | Azure Purview | AdventureworksLT | Data Governance with Azure Purview | [Code](https://github.com/DataSnowman/analytics-accelerator/tree/main/usecases/cdc/code) | [Steps](https://github.com/DataSnowman/purviewARM/blob/main/usecases/datagov/steps/usecasesteps.md) |

## Prerequisites

- Owner to the Azure Subscription being deployed. This is for creation of a separate Analytics Accelerator Resource Group and to delegate roles necessary for this deployment.

## Deploy Azure Purview

`Together with Azure Key Vault`

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FDataSnowman%2FpurviewARM%2Fmain%2Fworkspace%2FpurviewAccount%2Fazuredeploy.json) [![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FDataSnowman%2FpurviewARM%2Fmain%2Fworkspace%2FpurviewAccount%2Fazuredeploy.json)

This template deploys the following:

- Azure Purview
- Azure Key Vault