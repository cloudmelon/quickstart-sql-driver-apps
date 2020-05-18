# Quickstart Modern Application Development with SQL Drivers 

This repository stores Sample Helloworld Application written in different programing languages using SQL Drivers to connect SQL Server, Azure SQL Database and Big Data Clusters ( BDC ).


## Microsoft SQL Server & Azure SQL Database & Big Data Clusters ( BDC )

**Microsoft SQL Server** is a relational database management system developed by Microsoft. As a database server, it is a software product with the primary function of storing and retrieving data as requested by other software applications—which may run either on the same computer or on another computer across a network.

**Microsoft Azure SQL Database** is a managed cloud database provided as part of Microsoft Azure. A cloud database is a database that runs on a cloud computing platform, and access to it is provided as a service. Managed database services take care of scalability, backup, and high availability of the database.

**SQL Server Big Data Clusters ( BDC )** is a cloud native, platform agnostic, open data platform for analytics at any scale orchestrated by Kubernetes, it unites SQL Server with Apache Spark to deliver the best data analytics and machine learning experience, easy to use deployment. Delivered as part of the SQL Server 2019 release.


## SQL Server Connectors 

Microsoft provides a set of Connectivity driver for use with SQL Server, and Azure SQL Database. As of today, there are the following supported drivers : 

- ADO.Net for SQL Server
- JDBC Driver
- ODBC Driver
- Node.js driver
- Python Driver 
- Ruby Driver

To download SQL Server connectors : https://www.microsoft.com/en-gb/sql-server/sql-server-downloads


## How to deploy apps to Web App 

App Service on Linux provides pre-defined application stacks on Linux with support for languages such as .NET, PHP, Node.js and others. 

- Create a resource group 

``` 
az group create --name myResourceGroup --location "West Europe"

```

- Create an Azure App Service Plan

```
az appservice plan create --name myAppServicePlan --resource-group myResourceGroup --sku F1 --is-linux
```

- Create a web app 

```
# Bash
az webapp create --resource-group myResourceGroup --plan myAppServicePlan --name <app-name> --runtime <your runtime> --deployment-local-git
```


-- runtime flag

Ruby app : "RUBY|2.6.2" 



Run custom container : 
https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-docker

Create a multi-container (preview) app using a Docker Compose configuration
https://docs.microsoft.com/en-us/azure/app-service/containers/quickstart-multi-container


## Guide blog site 
Blog site : https://www.cloud-melon.com/

Share your insights with @MelonyQ at https://twitter.com/MelonyQ

## Guide book

- Implementing Microsoft Azure Infrastructure Solutions : Exam Guide 70-533
  https://www.packtpub.com/virtualization-and-cloud/implementing-microsoft-azure-infrastructure-solutions-exam-guide-70-533


- The Kubernetes Workshop 
  https://www.packtpub.com/gb/cloud-networking/the-kubernetes-workshop
