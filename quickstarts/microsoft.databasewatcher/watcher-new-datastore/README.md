---
description: This template lets you deploy a database watcher that uses a database on a new Azure Data Explorer cluster as its data store.
page_type: sample
products:
- azure
- azure-resource-manager
urlFragment: watcher-new-datastore
languages:
- json
---
# Create a database watcher with a new ADX data store

![Azure Public Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/PublicLastTestDate.svg)
![Azure Public Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/PublicDeployment.svg)

![Azure US Gov Last Test Date](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/FairfaxLastTestDate.svg)
![Azure US Gov Last Test Result](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/FairfaxDeployment.svg)

![Best Practice Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/BestPracticeResult.svg)
![Cred Scan Check](https://azurequickstartsservice.blob.core.windows.net/badges/quickstarts/microsoft.databasewatcher/watcher-new-datastore/CredScanResult.svg)

[![Deploy To Azure](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fquickstarts%2Fmicrosoft.databasewatcher%2Fwatcher-new-datastore%2Fazuredeploy.json)

[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2Fquickstarts%2Fmicrosoft.databasewatcher%2Fwatcher-new-datastore%2Fazuredeploy.json)

Use this template to:
- Create a [database watcher](https://learn.microsoft.com/azure/azure-sql/database-watcher-overview).
- Create an Azure Data Explorer cluster and a database on that cluster to be used as the [data store](https://learn.microsoft.com/azure/azure-sql/database-watcher-manage#manage-data-store) for the database watcher.
- Create Azure SQL Database and Azure SQL Managed Instance [targets](https://learn.microsoft.com/azure/azure-sql/database-watcher-manage#add-sql-targets-to-a-watcher) for the database watcher, using Microsoft Entra and SQL authentication.
- Create [managed private endpoints](https://learn.microsoft.com/azure/azure-sql/database-watcher-manage#create-a-managed-private-endpoint) for the database watcher to connect to an Azure SQL logical server and an Azure key vault using private connectivity.


## Prerequisites

See [Prerequisites](https://learn.microsoft.com/azure/azure-sql/database-watcher-manage#prerequisites).

## Deployment steps

You can click the "deploy to Azure" button at the beginning of this document or follow the instructions for command line deployment using the scripts in the root of this repo.

`Tags: Azure SQL, SQL monitoring, database watcher, Microsoft.DatabaseWatcher/watchers`
