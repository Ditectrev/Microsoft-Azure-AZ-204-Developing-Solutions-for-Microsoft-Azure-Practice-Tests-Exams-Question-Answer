# ⬆️ Microsoft Azure AZ 204 (Developing Solutions for Microsoft Azure) Practice Tests Exams Questions & Answers

![Promotional image](images/promotional.png)

## Table of Contents

| No. | Questions |
| --- | --------------------------- |
| 1   | [ You are implementing a software as a service (SaaS) ASP.NET Core web service that will run as an Azure Web App. The web service will use an on-premises SQL Server database for storage. The web service also includes a WebJob that processes data updates. Four customers will use the web service. Each instance of the WebJob processes data for a single customer and must run as a singleton instance. Each deployment must be tested by using deployment slots prior to serving production data. Azure costs must be minimized. Azure resources must be located in an isolated network. You need to configure the App Service plan for the Web App. How should you configure the App Service plan?](#question1) |
| 2   | [You are a developer for a software as a service (SaaS) company that uses an Azure Function to process orders. The Azure Function currently runs on an Azure Function app that is triggered by an Azure Storage queue. You are preparing to migrate the Azure Function to Kubernetes using Kubernetes-based Event Driven Autoscaling (KEDA). You need to configure Kubernetes Custom Resource Definitions (CRD) for the Azure Function. Which CRDs should you configure?](#question2) |
| 3   | [You are creating a CLI script that creates an Azure web app and related services in Azure App Service. The web app uses the following variables. You need to automatically deploy code from GitHub to the newly created web app. How should you complete the script?](#question3) |
| 4   | [You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Trigger the photo processing from Blob storage events. Does the solution meet the goal?](#question4) |
| 5   | [You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts. Does the solution meet the goal?](#question5) |
| 6   | [You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Enable auto swap for the Testing slot. Deploy the app to the Testing slot. Does the solution meet the goal?](#question6) |
| 7   | [You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Disable auto swap. Update the app with a method named statuscheck to run the scripts. Re-enable auto swap and deploy the app to the Production slot. Does the solution meet the goal?](#question7) |
| 8   | [You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Convert the Azure Storage account to a BlockBlobStorage storage account. Does the solution meet the goal?](#question8) |
| 9   | [You are developing an Azure Web App. You configure TLS mutual authentication for the web app. You need to validate the client certificate in the web app. To answer, select the appropriate options in the answer area.](#question9) |
| 10   | [You are developing a Docker/Go using Azure App Service Web App for Containers. You plan to run the container in an App Service on Linux. You identify a Docker container image to use. None of your current resource groups reside in a location that supports Linux. You must minimize the number of resource groups required. You need to create the application and perform an initial deployment. Which three Azure CLI commands should you use to develop the solution?](#question10) |
| 11   | [Fourth Coffee has an ASP.NET Core web app that runs in Docker. The app is mapped to the www.fourthcoffee.com domain. Fourth Coffee is migrating this application to Azure. You need to provision an App Service Web App to host this docker image and map the custom domain to the App Service web app. A resource group named FourthCoffeePublicWebResourceGroup has been created in the WestUS region that contains an App Service Plan named AppServiceLinuxDockerPlan. Which order should the CLI commands be used to develop the solution?](#question11) |
| 12   | [You are developing a serverless Java application on Azure. You create a new Azure Key Vault to work with secrets from a new Azure Functions application. The application must meet the following requirements: Reference the Azure Key Vault without requiring any changes to the Java code. Dynamically add and remove instances of the Azure Functions host based on the number of incoming application events. Ensure that instances are perpetually warm to avoid any cold starts. Connect to a VNet. Authentication to the Azure Key Vault instance must be removed if the Azure Function application is deleted. You need to grant the Azure Functions application access to the Azure Key Vault. Which three actions should you perform in sequence?](#question12) |
| 13   | [You develop a website. You plan to host the website in Azure. You expect the website to experience high traffic volumes after it is published. You must ensure that the website remains available and responsive while minimizing cost. You need to deploy the website. What should you do?](#question13) |
| 14   | [A company is developing a Java web app. The web app code is hosted in a GitHub repository located at https://github.com/Contoso/webapp. The web app must be evaluated before it is moved to production. You must deploy the initial code release to a deployment slot named staging. You need to create the web app and deploy the code. How should you complete the commands?](#question14) |
| 15   | [You have a web service that is used to pay for food deliveries. The web service uses Azure Cosmos DB as the data store. You plan to add a new feature that allows users to set a tip amount. The new feature requires that a property named tip on the document in Cosmos DB must be present and contain a numeric value. There are many existing websites and mobile apps that use the web service that will not be updated to set the tip property for some time. How should you complete the trigger?](#question15) |
| 16   | [You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Use the Durable Function async pattern to process the blob data. Does the solution meet the goal?](#question16) |
| 17   | [You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Pass the HTTP trigger payload into an Azure Service Bus queue to be processed by a queue trigger function and return an immediate HTTP success response. Does the solution meet the goal?](#question17) |
| 18   | [You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Configure the app to use an App Service hosting plan and enable the Always On setting. Does the solution meet the goal?](#question18) |
| 19   | [You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Move photo processing to an Azure Function triggered from the blob upload. Does the solution meet the goal?](#question19) |
| 20   | [You are developing an application that uses Azure Blob storage. The application must read the transaction logs of all the changes that occur to the blobs and the blob metadata in the storage account for auditing purposes. The changes must be in the order in which they occurred, include only create, update, delete, and copy operations and be retained for compliance reasons. You need to process the transaction logs asynchronously. What should you do?](#question20) |
| 21   | [You plan to create a Docker image that runs an ASP.NET Core application named ContosoApp. You have a setup script named setupScript.ps1 and a series of application files including ContosoApp.dll. You need to create a Dockerfile document that meets the following requirements: Call setupScripts.ps1 when the container is built. Run ContosoApp.dll when the container starts. The Dockerfile document must be created in the same folder where ContosoApp.dll and setupScript.ps1 are stored. Which five commands should you use to develop the solution?](#question21) |
| 22   | [You are developing an Azure Function App that processes images that are uploaded to an Azure Blob container. Images must be processed as quickly as possible after they are uploaded, and the solution must minimize latency. You create code to process images when the Function App is triggered. You need to configure the Function App. What should you do?](#question22) |
| 23   | [You are configuring a new development environment for a Java application. The environment requires a Virtual Machine Scale Set (VMSS), several storage accounts, and networking components. The VMSS must not be created until the storage accounts have been successfully created and an associated load balancer and virtual network is configured. How should you complete the Azure Resource Manager template?](#question23) |
| 24   | [You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 1: The code will log the time that the order was processed from the queue.](#question24) |
| 25   | [You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 2: When the ProcessOrders function fails, the function will retry up to five times for a given order, including the first try.](#question25) |
| 26   | [You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 3: When there are multiple orders in the queue, a batch of orders will be received from the queue and the ProcessOrders function will run multiple instances concurrently to process the orders.](#question26) |
| 27   | [You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 4: The ProcessOrders function will output the order to an Orders table in Azure Table Storage](#question27) |
| 28   | [You are developing a solution for a hospital to support the following use cases: The most recent patient status details must be retrieved even if multiple users in different locations have updated the patient record. Patient health monitoring data retrieved must be the current version or the prior version. After a patient is discharged and all charges have been assessed, the patient billing record contains the final charges. You provision a Cosmos DB NoSQL database and set the default consistency level for the database account to Strong. You set the value for Indexing Mode to Consistent. You need to minimize latency and any impact to the availability of the solution. You must override the default consistency level at the query level to meet the required consistency guarantees for the scenarios. Which consistency levels should you implement?](#question28) |
| 29   | [You are configuring a development environment for your team. You deploy the latest Visual Studio image from the Azure Marketplace to your Azure subscription. The development environment requires several software development kits (SDKs) and third-party components to support application development across the organization. You install and customize the deployed virtual machine (VM) for your development team. The customized VM must be saved to allow provisioning of a new team member development environment. You need to save the customized VM for future provisioning. Which tools or services should you use?](#question29) |
| 30   | [You are preparing to deploy a website to an Azure Web App from a GitHub repository. The website includes static content generated by a script. You plan to use the Azure Web App continuous deployment feature. You need to run the static generation script before the website starts serving traffic. What are two possible ways to achieve this goal?](#question30) |
| 31   | [You are developing an application to use Azure Blob storage. You have configured Azure Blob storage to include change feeds. A copy of your storage account must be created in another region. Data must be copied from the current storage account to the new storage account directly between the storage servers. You need to create a copy of the storage account in another region and copy the data. In which order should you perform the actions?](#question31) |
| 32   | [You are preparing to deploy an Azure virtual machine (VM)-based application. The VMs that run the application have the following requirements: When a VM is provisioned the firewall must be automatically configured before it can access Azure resources. Supporting services must be installed by using an Azure PowerShell script that is stored in Azure Storage. You need to ensure that the requirements are met. Which features should you use?](#question32) |
| 33   | [A company is developing a Node.js web app. The web app code is hosted in a GitHub repository located at https://github.com/TailSpinToys/webapp. The web app must be reviewed before it is moved to production. You must deploy the initial code release to a deployment slot named review. You need to create the web app and deploy the code. How should you complete the commands?](#question33) |
| 34   | [You are developing an application that needs access to an Azure virtual machine (VM). The access lifecycle for the application must be associated with the VM service instance. You need to enable managed identity for the VM. How should you complete the PowerShell segment?](#question34) |
| 35   | [You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Create an Azure Function app that uses the Consumption hosting model and that is triggered from the blob upload. Does the solution meet the goal?](#question35) |
| 36   | [You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Update the app with a method named statuscheck to run the scripts. Update the app settings for the app. Set the WEBSITE_SWAP_WARMUP_PING_PATH and WEBSITE_SWAP_WARMUP_PING_STATUSES with a path to the new method and appropriate response codes. Does the solution meet the goal?](#question36) |
| 37   | [You create the following PowerShell script. Question 1: A log alert is created that sends an email when the CPU percentage is above 60 percent for five minutes.](#question37) |
| 38   | [You create the following PowerShell script. Question 2: A log alert is created that sends an email when the number of machine heartbeates in the past hour is less than five.](#question38) |
| 39   | [You create the following PowerShell script. Question 3: The log alert is scheduled to run every two hours.](#question39) |
| 40   | [You are developing an Azure Function app. The app must meet the following requirements: Enable developers to write the functions by using the Rust language. Declaratively connect to an Azure Blob Storage account. You need to implement the app. Which Azure Function app features should you use?](#question40) |
| 41   | [You are developing an ASP.NET Core web application. You plan to deploy the application to Azure Web App for Containers. The application needs to store runtime diagnostic data that must be persisted across application restarts. You have the following code. You need to configure the application settings so that diagnostic data is stored as required. How should you configure the web app's settings?](#question41) |
| 42   | [You are developing a web app that is protected by Azure Web Application Firewall (WAF). All traffic to the web app is routed through an Azure Application Gateway instance that is used by multiple web apps. The web app address is contoso.azurewebsites.net.All traffic must be secured with SSL. The Azure Application Gateway instance is used by multiple web apps. You need to configure the Azure Application Gateway for the web app. Which two actions should you perform?](#question42) |
| 43   | [You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Use the Azure Blob Storage change feed to trigger photo processing. Does the solution meet the goal?](#question43) |
| 44   | [A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 1: SaveScore will work with Cosmos DB.](#question44) |
| 45   | [A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 2: SaveScore will update and replace a record if one already exists with the same playerId and gameId.](#question45) |
| 46   | [A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 3: Leader board data for the game will be automatically partitioned using gameId.](#question46) |
| 47   | [A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 4: SaveScore will store the values for the gameId and playerId parameters in the database.](#question47) |
| 48   | [You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 1: The code creates an infinite lease.](#question48) |
| 49   | [You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 2: The code at line 06 always creates a new blob.](#question49) |
| 50   | [You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 3: The finally block releases the lease.](#question50) |
| 51   | [You are building a website that uses Azure Blob storage for data storage. You configure Azure Blob storage lifecycle to move all blobs to the archive tier after 30 days. Customers have requested a service-level agreement (SLA) for viewing data older than 30 days. You need to document the minimum SLA for data recovery. Which SLA should you use?](#question51) |
| 52   | [You are developing a ticket reservation system for an airline. The storage solution for the application must meet the following requirements: Ensure at least 99.99% availability and provide low latency. Accept reservations even when localized network outages or other unforeseen failures occur. Process reservations in the exact sequence as reservations are submitted to minimize overbooking or selling the same seat to multiple travelers. Allow simultaneous and out-of-order reservations with a maximum five-second tolerance window. You provision a resource group named airlineResourceGroup in the Azure South-Central US region. You need to provision a SQL API Cosmos DB account to support the app. How should you complete the Azure CLI commands?](#question52) |
| 53   | [You are preparing to deploy a Python website to an Azure Web App using a container. The solution will use multiple containers in the same container group. The Dockerfile that builds the container is as follows: You build a container by using the following command. The Azure Container Registry instance named images is a private registry. The user name and password for the registry is admin. The Web App must always run the same version of the website regardless of future builds. You need to create an Azure Web App to run the website. How should you complete the commands?](#question53) |
| 54   | [You are developing a back-end Azure App Service that scales based on the number of messages contained in a Service Bus queue. A rule already exists to scale up the App Service when the average queue length of unprocessed and valid queue messages is greater than 1000. You need to add a new rule that will continuously scale down the App Service as long as the scale up condition is not met. How should you configure the Scale rule?](#question54) |
| 55   | [You have an application that uses Azure Blob storage. You need to update the metadata of the blobs. Which three methods should you use to develop the solution?](#question55) |
| 56   | [You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Event Grid. Configure the machine identifier as the partition key and enable capture. Does the solution meet the goal?](#question56) |
| 57   | [You develop Azure solutions. A .NET application needs to receive a message each time an Azure virtual machine finishes processing data. The messages must NOT persist after being processed by the receiving application. You need to implement the .NET object that will receive the messages. Which object should you use?](#question57) |
| 58   | [You are maintaining an existing application that uses an Azure Blob GPv1 Premium storage account. Data older than three months is rarely used. Data newer than three months must be available immediately. Data older than a year must be saved but does not need to be available immediately. You need to configure the account to support a lifecycle management rule that moves blob data to archive storage for data not modified in the last year. Which three actions should you perform in sequence?](#question58) |
| 59   | [You develop Azure solutions. You must connect to a No-SQL globally-distributed database by using the .NET API. You need to create an object to configure and execute requests in the database. Which code segment should you use?](#question59) |
| 60   | [You have an existing Azure storage account that stores large volumes of data across multiple containers. You need to copy all data from the existing storage account to a new storage account. The copy process must meet the following requirements: Automate data movement. Minimize user input required to perform the operation. Ensure that the data movement process is recoverable. What should you use?](#question60) |
| 61   | [Question61](#question61) |
| 62   | [Question62](#question62) |
| 63   | [Question63](#question63) |
| 64   | [Question64](#question64) |
| 65   | [Question65](#question65) |
| 66   | [Question66](#question66) |
| 67   | [Question67](#question67) |
| 68   | [Question68](#question68) |
| 69   | [Question69](#question69) |
| 70   | [Question70](#question70) |
| 71   | [Question71](#question71) |
| 72   | [Question72](#question72) |
| 73   | [Question73](#question73) |
| 74   | [Question74](#question74) |
| 75   | [Question75](#question75) |
| 76   | [Question76](#question76) |
| 77   | [Question77](#question77) |
| 78   | [Question78](#question78) |
| 79   | [Question79](#question79) |
| 80   | [Question80](#question80) |
| 81   | [Question81](#question81) |
| 82   | [Question82](#question82) |
| 83   | [Question83](#question83) |
| 84   | [Question84](#question84) |
| 85   | [Question85](#question85) |
| 86   | [Question86](#question86) |
| 87   | [Question87](#question87) |
| 88   | [Question88](#question88) |
| 89   | [Question89](#question89) |
| 90   | [Question90](#question90) |
| 91   | [Question91](#question91) |
| 92   | [Question92](#question92) |
| 93   | [Question93](#question93) |
| 94   | [Question94](#question94) |
| 95   | [Question95](#question95) |
| 96   | [Question96](#question96) |
| 97   | [Question97](#question97) |
| 98   | [Question98](#question98) |
| 99   | [Question99](#question99) |
| 100   | [Question100](#question100) |
| 101   | [Question101](#question101) |
| 102   | [Question102](#question102) |
| 103   | [Question103](#question103) |
| 104   | [Question104](#question104) |
| 105   | [Question105](#question105) |
| 106   | [Question106](#question106) |
| 107   | [Question107](#question107) |
| 108   | [Question108](#question108) |
| 109   | [Question109](#question109) |
| 110   | [Question110](#question110) |
| 111   | [Question111](#question111) |
| 112   | [Question112](#question112) |
| 113   | [Question113](#question113) |
| 114   | [Question114](#question114) |
| 115   | [Question115](#question115) |
| 116   | [Question116](#question116) |
| 117   | [Question117](#question117) |
| 118   | [Question118](#question118) |
| 119   | [Question119](#question119) |
| 110   | [Question110](#question110) |
| 111   | [Question111](#question111) |
| 112   | [Question112](#question112) |
| 113   | [Question113](#question113) |
| 114   | [Question114](#question114) |
| 115   | [Question115](#question115) |
| 116   | [Question116](#question116) |
| 117   | [Question117](#question117) |
| 118   | [Question118](#question118) |
| 119   | [Question119](#question119) |
| 120   | [Question120](#question120) |
| 121   | [Question121](#question121) |
| 122   | [Question122](#question122) |
| 123   | [Question123](#question123) |
| 124   | [Question124](#question124) |
| 125   | [Question125](#question125) |
| 126   | [Question126](#question126) |
| 127   | [Question127](#question127) |
| 128   | [Question128](#question128) |
| 129   | [Question129](#question129) |
| 130   | [Question130](#question130) |
| 131   | [Question131](#question131) |
| 132   | [Question132](#question132) |
| 133   | [Question133](#question133) |
| 134   | [Question134](#question134) |
| 135   | [Question135](#question135) |
| 136   | [Question136](#question136) |
| 137   | [Question137](#question137) |
| 138   | [Question138](#question138) |
| 139   | [Question139](#question139) |
| 140   | [Question140](#question140) |
| 141   | [Question141](#question141) |
| 142   | [Question142](#question142) |
| 143   | [Question143](#question143) |
| 144   | [Question144](#question144) |
| 145   | [Question145](#question145) |
| 146   | [Question146](#question146) |
| 147   | [Question147](#question147) |
| 148   | [Question148](#question148) |
| 149   | [Question149](#question149) |
| 150   | [Question150](#question150) |
| 151   | [Question151](#question151) |
| 152   | [Question152](#question152) |
| 153   | [Question153](#question153) |
| 154   | [Question154](#question154) |
| 155   | [Question155](#question155) |
| 156   | [Question156](#question156) |
| 157   | [Question157](#question157) |
| 158   | [Question158](#question158) |
| 159   | [Question159](#question159) |
| 160   | [Question160](#question160) |
| 161   | [Question161](#question161) |
| 162   | [Question162](#question162) |
| 163   | [Question163](#question163) |
| 164   | [Question164](#question164) |
| 165   | [Question165](#question165) |
| 166   | [Question166](#question166) |
| 167   | [Question167](#question167) |
| 168   | [Question168](#question168) |
| 169   | [Question169](#question169) |
| 170   | [Question170](#question170) |<------------ Nie podano odpowiedzi, nie wiem jak zrobić.
| 171   | [Question171](#question171) |
| 172   | [Question172](#question172) |
| 173   | [Question173](#question173) |
| 174   | [Question174](#question174) |
| 175   | [Question175](#question175) |
| 176   | [Question176](#question176) |
| 177   | [Question177](#question177) |
| 178   | [Question178](#question178) |
| 179   | [Question179](#question179) |
| 180   | [Question180](#question180) |
| 181   | [Question181](#question181) |
| 182   | [Question182](#question182) |
| 183   | [Question183](#question183) |
| 184   | [Question184](#question184) |
| 185   | [Question185](#question185) |
| 186   | [Question186](#question186) |
| 187   | [Question187](#question187) |
| 188   | [Question188](#question188) |
| 189   | [Question189](#question189) |
| 190   | [Question190](#question190) |
| 191   | [Question191](#question191) |
| 192   | [Question192](#question192) |
| 193   | [Question193](#question193) |
| 194   | [Question194](#question194) |
| 195   | [Question195](#question195) |
| 196   | [Question196](#question196) |
| 197   | [Question197](#question197) |
| 198   | [Question198](#question198) |
| 199   | [Question199](#question199) |
| 200   | [Question200](#question200) |
| 201   | [Question201](#question201) |
| 202   | [Question202](#question202) |
| 203   | [Question203](#question203) |
| 204   | [Question204](#question204) |  <------ Nie wiem jak zrobić, nie podali odpowiedzi
| 205   | [Question205](#question205) |
| 206   | [Question206](#question206) |
| 207   | [Question207](#question207) |
| 208   | [Question208](#question208) |


### You are implementing a software as a service (SaaS) ASP.NET Core web service that will run as an Azure Web App. The web service will use an on-premises SQL Server database for storage. The web service also includes a WebJob that processes data updates. Four customers will use the web service. Each instance of the WebJob processes data for a single customer and must run as a singleton instance. Each deployment must be tested by using deployment slots prior to serving production data. Azure costs must be minimized. Azure resources must be located in an isolated network. You need to configure the App Service plan for the Web App. How should you configure the App Service plan?

![Question 1](images/question1.jpeg)

- [ ] Number of VM instances: 2. Pricing tier: Isolated.
- [ ] Number of VM instances: 4. Pricing tier: Isolated.
- [ ] Number of VM instances: 8. Pricing tier: Standard.
- [ ] Number of VM instances: 16. Pricing tier: Premium.
- [x] Number of VM instances: 4. Pricing tier: Isolated.
- [ ] Number of VM instances: 4. Pricing tier: Consumption.

**[⬆ Back to Top](#table-of-contents)**

### You are a developer for a software as a service (SaaS) company that uses an Azure Function to process orders. The Azure Function currently runs on an Azure Function app that is triggered by an Azure Storage queue. You are preparing to migrate the Azure Function to Kubernetes using Kubernetes-based Event Driven Autoscaling (KEDA). You need to configure Kubernetes Custom Resource Definitions (CRD) for the Azure Function. Which CRDs should you configure?

![Question 2](images/question2.jpeg)

- [x] Box 1, CRD type: Deployment. Box 2, CRD type: ScaledObject. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: Secret. Box 2, CRD type: ScaledObject. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: TriggerAuthentication. Box 2, CRD type: Deployment. Box 3, CRD type: Secret.
- [ ] Box 1, CRD type: Deployment. Box 2, CRD type: ScaledObject. Box 3, CRD type: TriggerAuthentication.

**[⬆ Back to Top](#table-of-contents)**

![Question 3 part 1](images/question3_1.png)
![Question 3 part 2](images/question3_2.jpeg)

### You are creating a CLI script that creates an Azure web app and related services in Azure App Service. The web app uses the following variables. You need to automatically deploy code from GitHub to the newly created web app. How should you complete the script?

- [ ] Box 1: az webapp. Box 2: az webapp create. Box 3: git clone $gitrepo. Box 4: az webapp. Box 5: --plan $webappname
- [x] Box 1: az appservice plan create. Box 2: az webapp create. Box 3: --plan $webappname. Box 4: az webapp deployment. Box 5: --repo-url $gitrepo --branch master --manual-integration
- [ ] Box 1: az appservice plan create. Box 2: az webapp deployment. Box 3: --plan $webappname. Box 4: az webapp deployment. Box 5: --repo-url $gitrepo --branch master --manual-integration
- [ ] Box 1: az group delete. Box 2: az webapp create. Box 3: git clone $gitrepo. Box 4: az appservice plan create. Box 5: git clone $gitrepo

**[⬆ Back to Top](#table-of-contents)**

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Trigger the photo processing from Blob storage events. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Update the web.config file to include the applicationInitialization configuration element. Specify custom initialization actions to run the scripts. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Enable auto swap for the Testing slot. Deploy the app to the Testing slot. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Disable auto swap. Update the app with a method named statuscheck to run the scripts. Re-enable auto swap and deploy the app to the Production slot. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Convert the Azure Storage account to a BlockBlobStorage storage account. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Web App. You configure TLS mutual authentication for the web app. You need to validate the client certificate in the web app. To answer, select the appropriate options in the answer area.

![Question 9](images/question9.jpeg)

- [ ] Client certificate location: Client cookie. Encoding type: URL.
- [ ] Client certificate location: HTTP message body. Encoding type: Base64.
- [ ] Client certificate location: HTTP request header. Encoding type: Unicode.
- [x] Client certificate location: HTTP request header. Encoding type: Base64.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a Docker/Go using Azure App Service Web App for Containers. You plan to run the container in an App Service on Linux. You identify a Docker container image to use. None of your current resource groups reside in a location that supports Linux. You must minimize the number of resource groups required. You need to create the application and perform an initial deployment. Which three Azure CLI commands should you use to develop the solution?

![Question 10](images/question10.png)

- [ ] Box 1: az webapp create. Box 2: az appservice plan create. Box 3: az group create.
- [ ] Box 1: az appservice plan create. Box 2: az group create. Box 3: az group update.
- [x] Box 1: az group create. Box 2: az appservice plan create. Box 3: az webapp create.
- [ ] Box 1: az appservice plan create. Box 2: az webapp create. Box 3: az webapp update.

**[⬆ Back to Top](#table-of-contents)**

### Fourth Coffee has an ASP.NET Core web app that runs in Docker. The app is mapped to the www.fourthcoffee.com domain. Fourth Coffee is migrating this application to Azure. You need to provision an App Service Web App to host this docker image and map the custom domain to the App Service web app. A resource group named FourthCoffeePublicWebResourceGroup has been created in the WestUS region that contains an App Service Plan named AppServiceLinuxDockerPlan. Which order should the CLI commands be used to develop the solution?

![Question 11](images/question11.jpeg)

- [x] Box 1: #/bin/bash appName="FourthCoffeePublicWeb$random" location="WestUS" dockerHubContainerPath="FourthCoffee/publicweb:v1" fqdn="http://www.fourthcoffee.com">www.fourthcoffee.com. Box 2: az webapp create --name $appName --plan AppServiceLinuxDockerPlan --resource-group fourthCoffeePublicWebResourceGroup. Box 3: az webapp config container set --docker-custom-image-name $dockerHubContainerPath --name $appName --resource-group fourthCoffeePublicWebResourceGroup. Box 4: az webapp config hostname add --webapp-name $appName --resource-group fourthCoffeePublicWebResourceGroup --hostname $fqdn.
- [ ] #/bin/bash appName="FourthCoffeePublicWeb$random" location="WestUS" dockerHubContainerPath="FourthCoffee/publicweb:v1" fqdn="http://www.fourthcoffee.com">www.fourthcoffee.com. Box 2: az webapp create --name $appName --plan AppServiceLinuxDockerPlan --resource-group fourthCoffeePublicWebResourceGroup. Box 3: az webapp config hostname add --webapp-name $appName --resource-group fourthCoffeePublicWebResourceGroup --hostname $fqdn. Box 4: az webapp config container set --docker-custom-image-name $dockerHubContainerPath --name $appName --resource-group fourthCoffeePublicWebResourceGroup.
- [ ] Box 1: az webapp config container set --docker-custom-image-name $dockerHubContainerPath --name $appName --resource-group fourthCoffeePublicWebResourceGroup. Box 2: az webapp create --name $appName --plan AppServiceLinuxDockerPlan --resource-group fourthCoffeePublicWebResourceGroup. Box 3: az webapp config hostname add --webapp-name $appName --resource-group fourthCoffeePublicWebResourceGroup --hostname $fqdn.. Box 4: #/bin/bash appName="FourthCoffeePublicWeb$random" location="WestUS" dockerHubContainerPath="FourthCoffee/publicweb:v1" fqdn="http://www.fourthcoffee.com">www.fourthcoffee.com..
- [ ] Box 1: az webapp config hostname add --webapp-name $appName --resource-group fourthCoffeePublicWebResourceGroup --hostname $fqdn. Box 2: az webapp create --name $appName --plan AppServiceLinuxDockerPlan --resource-group fourthCoffeePublicWebResourceGroup. Box 3: #/bin/bash appName="FourthCoffeePublicWeb$random" location="WestUS" dockerHubContainerPath="FourthCoffee/publicweb:v1" fqdn="http://www.fourthcoffee.com">www.fourthcoffee.com. Box 4: az webapp config container set --docker-custom-image-name $dockerHubContainerPath --name $appName --resource-group fourthCoffeePublicWebResourceGroup.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a serverless Java application on Azure. You create a new Azure Key Vault to work with secrets from a new Azure Functions application. The application must meet the following requirements: Reference the Azure Key Vault without requiring any changes to the Java code. Dynamically add and remove instances of the Azure Functions host based on the number of incoming application events. Ensure that instances are perpetually warm to avoid any cold starts. Connect to a VNet. Authentication to the Azure Key Vault instance must be removed if the Azure Function application is deleted. You need to grant the Azure Functions application access to the Azure Key Vault. Which three actions should you perform in sequence?

![Question 12](images/question12.png)

- [ ] Box 1: Create the Azure Functions app with a Consumption plan type. Box 2: Create an access policy in Azure Key Vault for the application identity. Box 3: Create a user-assigned managed identity for the application.
- [x] Box 1: Create the Azure Functions app with a Premium plan type. Box 2: Create a user-assigned managed identity for the application. Box 3: Create an access policy in Azure Key Vault for the application identity.
- [ ] Box 1: Create the Azure Functions app with a Consumption plan type. Box 2: Create a user-assigned managed identity for the application. Box 3: Create an access policy in Azure Key Vault for the application identity.
- [ ] Box 1: Create the Azure Functions app with a Premium plan type. Box 2: Create a user-assigned managed identity for the application. Box 3: Create an access policy in Azure Key Vault for the application identity.

**[⬆ Back to Top](#table-of-contents)**

### You develop a website. You plan to host the website in Azure. You expect the website to experience high traffic volumes after it is published. You must ensure that the website remains available and responsive while minimizing cost. You need to deploy the website. What should you do?

- [ ] Deploy the website to a virtual machine. Configure the virtual machine to automatically scale when the CPU load is high.
- [ ] Deploy the website to an App Service that uses the Shared service tier. Configure the App Service plan to automatically scale when the CPU load is high.
- [ ] Deploy the website to a virtual machine. Configure a Scale Set to increase the virtual machine instance count when the CPU load is high.
- [x] Deploy the website to an App Service that uses the Standard service tier. Configure the App Service plan to automatically scale when the CPU load is high.

**[⬆ Back to Top](#table-of-contents)**

![Question 14](images/question14.png)

### A company is developing a Java web app. The web app code is hosted in a GitHub repository located at https://github.com/Contoso/webapp. The web app must be evaluated before it is moved to production. You must deploy the initial code release to a deployment slot named staging. You need to create the web app and deploy the code. How should you complete the commands?

- [x] Box 1: group. Box 2: appservice plan. Box 3: webapp. Box 4: webapp deployment slot. Box 5: webapp deployment source.
- [ ] Box 1: appservice plan. Box 2: group. Box 3: webapp. Box 4: webapp deployment slot. Box 5: webapp deployment source.
- [ ] Box 1: webapp. Box 2: group. Box 3: webapp deployment source. Box 4: webapp deployment slot. Box 5: appservice plan.
- [ ] Box 1: webapp. Box 2: group. Box 3: webapp deployment source. Box 4: webapp deployment slot. Box 5: appservice plan.

**[⬆ Back to Top](#table-of-contents)**

![Question 15](images/question15.jpeg)

### You have a web service that is used to pay for food deliveries. The web service uses Azure Cosmos DB as the data store. You plan to add a new feature that allows users to set a tip amount. The new feature requires that a property named tip on the document in Cosmos DB must be present and contain a numeric value. There are many existing websites and mobile apps that use the web service that will not be updated to set the tip property for some time. How should you complete the trigger?

- [ ] Box 1: __value();. Box 2: if (request.getValue("tip") === null) {. Box 3: __.upsertDocument(i);.
- [ ] Box 1: __readDocument()('item');. Box 2: if (!("tip" in i)) {. Box 3: __.replaceDocument(i);.
- [x] Box 1: getContext().getRequest();. Box 2: if (!("tip" in i)) {. Box 3: r.setBody(i);.
- [ ] Box 1: getContext().getRequest();. Box 2: if (isNaN(i)["tip"] || i["tip"] === null) {. Box 3: r.setValue(i);.

**[⬆ Back to Top](#table-of-contents)**

### You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Use the Durable Function async pattern to process the blob data. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Pass the HTTP trigger payload into an Azure Service Bus queue to be processed by a queue trigger function and return an immediate HTTP success response. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop an HTTP triggered Azure Function app to process Azure Storage blob data. The app is triggered using an output binding on the blob. The app continues to time out after four minutes. The app must process the blob data. You need to ensure the app does not time out and processes the blob data. Solution: Configure the app to use an App Service hosting plan and enable the Always On setting. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Move photo processing to an Azure Function triggered from the blob upload. Does the solution meet the goal?

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that uses Azure Blob storage. The application must read the transaction logs of all the changes that occur to the blobs and the blob metadata in the storage account for auditing purposes. The changes must be in the order in which they occurred, include only create, update, delete, and copy operations and be retained for compliance reasons. You need to process the transaction logs asynchronously. What should you do?

- [ ] Process all Azure Blob storage events by using Azure Event Grid with a subscriber Azure Function app.
- [x] Enable the change feed on the storage account and process all changes for available events.
- [ ] Process all Azure Storage Analytics logs for successful blob events.
- [ ] Use the Azure Monitor HTTP Data Collector API and scan the request body for successful blob events.

**[⬆ Back to Top](#table-of-contents)**

### You plan to create a Docker image that runs an ASP.NET Core application named ContosoApp. You have a setup script named setupScript.ps1 and a series of application files including ContosoApp.dll. You need to create a Dockerfile document that meets the following requirements: Call setupScripts.ps1 when the container is built. Run ContosoApp.dll when the container starts. The Dockerfile document must be created in the same folder where ContosoApp.dll and setupScript.ps1 are stored. Which five commands should you use to develop the solution?

![Question 21](images/question21.png)

- [ ] Box 1: CMD ["dotnet", "ContosoApp.dll"]. Box 2: FROM microsoft/aspnetcore:latest. Box 3: RUN powershell ./setupScript.ps1. Box 4: WORKDIR /apps/ContosoApp. Box 5: COPY ./ ..
- [ ] Box 1: COPY ./ ... Box 2: RUN powershell ./setupScript.ps1. Box 3: FROM microsoft/aspnetcore:latest. Box 4: CMD ["dotnet", "ContosoApp.dll"]. Box 5: WORKDIR /apps/ContosoApp.
- [ ] Box 1: RUN powershell ./setupScript.ps1. Box 2: CMD ["dotnet", "ContosoApp.dll"]. Box 3: FROM microsoft/aspnetcore:latest. Box 4: WORKDIR /apps/ContosoApp. Box 5: COPY ./ ..
- [x] Box 1: FROM microsoft/aspnetcore:latest. Box 2: WORKDIR /apps/ContosoApp. Box 3: COPY ./ .. Box 4: RUN powershell ./setupScript.ps1. Box 5: CMD ["dotnet", "ContosoApp.dll"].

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function App that processes images that are uploaded to an Azure Blob container. Images must be processed as quickly as possible after they are uploaded, and the solution must minimize latency. You create code to process images when the Function App is triggered. You need to configure the Function App. What should you do?

- [ ] Use an App Service plan. Configure the Function App to use an Azure Blob Storage input trigger.
- [ ] Use a Consumption plan. Configure the Function App to use an Azure Blob Storage trigger.
- [ ] Use a Consumption plan. Configure the Function App to use a Timer trigger.
- [x] Use an App Service plan. Configure the Function App to use an Azure Blob Storage trigger.
- [ ] Use a Consumption plan. Configure the Function App to use an Azure Blob Storage input trigger.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring a new development environment for a Java application. The environment requires a Virtual Machine Scale Set (VMSS), several storage accounts, and networking components. The VMSS must not be created until the storage accounts have been successfully created and an associated load balancer and virtual network is configured. How should you complete the Azure Resource Manager template?

![Question 23](images/question23.png)

- [x] Box 1: copyIndex. Box 2: copy. Box 3: dependsOn.
- [ ] Box 1: copy. Box 2: copyIndex. Box 3: dependsOn.
- [ ] Box 1: priority. Box 2: dependsOn. Box 3: copyIndex.
- [ ] Box 1: priority. Box 2: copyIndex. Box 3: dependsOn.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 1: The code will log the time that the order was processed from the queue.

![Question 24](images/question24_25_26_27.png)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 2: When the ProcessOrders function fails, the function will retry up to five times for a given order, including the first try.

![Question 25](images/question24_25_26_27.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 3: When there are multiple orders in the queue, a batch of orders will be received from the queue and the ProcessOrders function will run multiple instances concurrently to process the orders.

![Question 26](images/question24_25_26_27.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function App by using Visual Studio. The app will process orders input by an Azure Web App. The web app places the order information into Azure Queue Storage. You need to review the Azure Function App code shown below. Question 4: The ProcessOrders function will output the order to an Orders table in Azure Table Storage.

![Question 27](images/question24_25_26_27.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution for a hospital to support the following use cases: The most recent patient status details must be retrieved even if multiple users in different locations have updated the patient record. Patient health monitoring data retrieved must be the current version or the prior version. After a patient is discharged and all charges have been assessed, the patient billing record contains the final charges. You provision a Cosmos DB NoSQL database and set the default consistency level for the database account to Strong. You set the value for Indexing Mode to Consistent. You need to minimize latency and any impact to the availability of the solution. You must override the default consistency level at the query level to meet the required consistency guarantees for the scenarios. Which consistency levels should you implement?

![Question 28](images/question28.png)

- [ ] Box 1: Strong. Box 2: Consistent Prefix. Box 3: Eventual.
- [ ] Box 1: Eventual. Box 2: Strong. Box 3: Bounded Staleness.
- [ ] Box 1: Consistent Prefix. Box 2: Bounded Staleness. Box 3: Eventual.
- [x] Box 1: Strong. Box 2: Bounded Staleness. Box 3: Eventual.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring a development environment for your team. You deploy the latest Visual Studio image from the Azure Marketplace to your Azure subscription. The development environment requires several software development kits (SDKs) and third-party components to support application development across the organization. You install and customize the deployed virtual machine (VM) for your development team. The customized VM must be saved to allow provisioning of a new team member development environment. You need to save the customized VM for future provisioning. Which tools or services should you use?

![Question 29](images/question29.png)

- [ ] Generalize the VM: Visual Studio command prompt. Store images: Azure Data Lake Storage.
- [x] Generalize the VM: Azure PowerShell. Store images: Azure Blob Storage.
- [ ] Generalize the VM: Visual Studio command prompt. Store images: Azure File Storage.
- [ ] Generalize the VM: Azure PowerShell. Store images: Azure File Storage.

**[⬆ Back to Top](#table-of-contents)**

### You are preparing to deploy a website to an Azure Web App from a GitHub repository. The website includes static content generated by a script. You plan to use the Azure Web App continuous deployment feature. You need to run the static generation script before the website starts serving traffic. What are two possible ways to achieve this goal?

- [ ] Add the path to the static content generation tool to WEBSITE_RUN_FROM_PACKAGE setting in the host.json file.
- [x] Add a PreBuild target in the websites csproj project file that runs the static content generation script.
- [ ] Create a file named run.cmd in the folder /run that calls a script which generates the static content and deploys the website.
- [x] Create a file named .deployment in the root of the repository that calls a script which generates the static content and deploys the website.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application to use Azure Blob storage. You have configured Azure Blob storage to include change feeds. A copy of your storage account must be created in another region. Data must be copied from the current storage account to the new storage account directly between the storage servers. You need to create a copy of the storage account in another region and copy the data. In which order should you perform the actions?

![Question 31](images/question31.jpeg)

- [ ] Box 1: Create a new template deployment. Box 2: Export a Resource Manager template. Box 3: Modify the template by changing the storage account name and region. Box 4: Deploy the template to create a new storage account in the target region. Box 5: Use AZCopy to copy the data to the new storage account.
- [ ] Box 1: Use AZCopy to copy the data to the new storage account. Box 2: Create a new template deployment. Box 3: Modify the template by changing the storage account name and region. Box 4: Deploy the template to create a new storage account in the target region. Box 5: Export a Resource Manager template.
- [x] Box 1: Export a Resource Manager template. Box 2: Create a new template deployment. Box 3: Modify the template by changing the storage account name and region. Box 4: Deploy the template to create a new storage account in the target region. Box 5: Use AZCopy to copy the data to the new storage account.
- [ ] Box 1: Use AZCopy to copy the data to the new storage account. Box 2: Create a new template deployment. Box 3: Modify the template by changing the storage account name and region. Box 4: Deploy the template to create a new storage account in the target region. Box 5: Export a Resource Manager template.

**[⬆ Back to Top](#table-of-contents)**

### You are preparing to deploy an Azure virtual machine (VM)-based application. The VMs that run the application have the following requirements: When a VM is provisioned the firewall must be automatically configured before it can access Azure resources. Supporting services must be installed by using an Azure PowerShell script that is stored in Azure Storage. You need to ensure that the requirements are met. Which features should you use?

![Question 32](images/question32.jpeg)

- [ ] Firewall configuration: Run Command. Supporting services script: Hybrid Runbook Worker.
- [ ] Firewall configuration: Customer Script Extension. Supporting services script: Serial console.
- [x] Firewall configuration: Run Command. Supporting services script: Customer Script Extension.
- [ ] Firewall configuration: Hybrid Runbook Worker. Supporting services script: Customer Script Extension.

**[⬆ Back to Top](#table-of-contents)**

### A company is developing a Node.js web app. The web app code is hosted in a GitHub repository located at https://github.com/TailSpinToys/webapp. The web app must be reviewed before it is moved to production. You must deploy the initial code release to a deployment slot named review. You need to create the web app and deploy the code. How should you complete the commands?

![Question 33](images/question33.jpeg)

- [ ] Box 1: New-AzWebAppSlot. Box 2: New-AzWebApp. Box 3: New-AzAppServicePlan. Box 4: New-AzResourceGroup.
- [x] Box 1: New-AzResourceGroup. Box 2: New-AzAppServicePlan. Box 3: New-AzWebApp. Box 4: New-AzWebAppSlot.
- [ ] Box 1: New-AzWebAppSlot. Box 2: New-AzAppServicePlan. Box 3: New-AzWebApp. Box 4: New-AzResourceGroup.
- [ ] Box 1: New-AzResourceGroup. Box 2: New-AzAppServicePlan. Box 3: New-AzWebAppSlot. Box 4: New-AzWebApp.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that needs access to an Azure virtual machine (VM). The access lifecycle for the application must be associated with the VM service instance. You need to enable managed identity for the VM. How should you complete the PowerShell segment?

![Question 34](images/question34.jpeg)

- [ ] Box 1: -AssignIdentity:. Box 2: $SystemAssigned.
- [ ] Box 1: -AssignIdentity:. Box 2: $UserAssigned.
- [x] Box 1: -IdentityId: (note: screenshot has mistake, it should be "-IdentityType:" in the dropdown). Box 2: $SystemAssigned.
- [ ] Box 1: -IdentityId: (note: screenshot has mistake, it should be "-IdentityType:" in the dropdown). Box 2: $UserAssigned.

**[⬆ Back to Top](#table-of-contents)**

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Create an Azure Function app that uses the Consumption hosting model and that is triggered from the blob upload. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure App Service API app to a Windows-hosted deployment slot named Development. You create additional deployment slots named Testing and Production. You enable auto swap on the Production deployment slot. You need to ensure that scripts run and resources are available before a swap operation occurs. Solution: Update the app with a method named statuscheck to run the scripts. Update the app settings for the app. Set the WEBSITE_SWAP_WARMUP_PING_PATH and WEBSITE_SWAP_WARMUP_PING_STATUSES with a path to the new method and appropriate response codes. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You create the following PowerShell script. Question 1: A log alert is created that sends an email when the CPU percentage is above 60 percent for five minutes.

![Question 37](images/question37_38_39.png)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You create the following PowerShell script. Question 2: A log alert is created that sends an email when the number of machine heartbeates in the past hour is less than five.

![Question 38](images/question37_38_39.png)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You create the following PowerShell script. Question 3: The log alert is scheduled to run every two hours.

![Question 39](images/question37_38_39.png)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Function app. The app must meet the following requirements: Enable developers to write the functions by using the Rust language. Declaratively connect to an Azure Blob Storage account. You need to implement the app. Which Azure Function app features should you use?

![Question 40](images/question40.png)

- [ ] Enable developers to write the functions by using the Rust language: Hosting plan. Declaratively connect to an Azure Blog Storage account: Custom handler.
- [ ] Enable developers to write the functions by using the Rust language: Runtime. Declaratively connect to an Azure Blog Storage account: Policy.
- [ ] Enable developers to write the functions by using the Rust language: Custom handler. Declaratively connect to an Azure Blog Storage account: Trigger.
- [x] Enable developers to write the functions by using the Rust language: Custom handler. Declaratively connect to an Azure Blog Storage account: Extension bundle.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an ASP.NET Core web application. You plan to deploy the application to Azure Web App for Containers. The application needs to store runtime diagnostic data that must be persisted across application restarts. You have the following code. You need to configure the application settings so that diagnostic data is stored as required. How should you configure the web app's settings?

![Question 41 part 1](images/question41_1.jpeg)
![Question 41 part 2](images/question41_2.jpeg)

- [x] App setting: WEBSITES_ENABLE_APP_SERVICE_STORAGE. Value: /home.
- [ ] App setting: WEBSITES_ENABLE_APP_SERVICE_STORAGE. Value: /local.
- [ ] App setting: LOCALAPPDATA. Value: D:\home.
- [ ] App setting: DOTNET_HOSTING_OPTIMIZATION_CACHE. Value: D:\home.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app that is protected by Azure Web Application Firewall (WAF). All traffic to the web app is routed through an Azure Application Gateway instance that is used by multiple web apps. The web app address is contoso.azurewebsites.net.All traffic must be secured with SSL. The Azure Application Gateway instance is used by multiple web apps. You need to configure the Azure Application Gateway for the web app. Which two actions should you perform?

- [x] In the Azure Application Gateway's HTTP setting, enable the Use for App service setting.
- [ ] Convert the web app to run in an Azure App service environment (ASE).
- [ ] Add an authentication certificate for contoso.azurewebsites.net to the Azure Application Gateway.
- [x] In the Azure Application Gateway's HTTP setting, set the value of the Override backend path option to contoso22.azurewebsites.net.

**[⬆ Back to Top](#table-of-contents)**

### You develop a software as a service (SaaS) offering to manage photographs. Users upload photos to a web service which then stores the photos in Azure Storage Blob storage. The storage account type is General-purpose V2. When photos are uploaded, they must be processed to produce and save a mobile-friendly version of the image. The process to produce a mobile-friendly version of the image must start in less than one minute. You need to design the process that starts the photo processing. Solution: Use the Azure Blob Storage change feed to trigger photo processing. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 1: SaveScore will work with Cosmos DB.

![Question 44 part 1](images/question44_45_46_47_1.png)
![Question 44 part 2](images/question44_45_46_47_2.png)
![Question 44 part 3](images/question44_45_46_47_3.jpeg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 2: SaveScore will update and replace a record if one already exists with the same playerId and gameId.

![Question 45 part 1](images/question44_45_46_47_1.png)
![Question 45 part 2](images/question44_45_46_47_2.png)
![Question 45 part 3](images/question44_45_46_47_3.jpeg)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 3: Leader board data for the game will be automatically partitioned using gameId.

![Question 46 part 1](images/question44_45_46_47_1.png)
![Question 46 part 2](images/question44_45_46_47_2.png)
![Question 46 part 3](images/question44_45_46_47_3.jpeg)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### A company develops a series of mobile games. All games use a single leaderboard service. You have the following requirements: Code must be scalable and allow for growth. Each record must consist of a playerId, gameId, score, and time played. When users reach a new high score, the system will save the new score using the SaveScore function below. Each game is assigned an Id based on the series title. You plan to store customer information in Azure Cosmos DB. The following data already exists in the database: You develop the following code to save scores in the data store. (Line numbers are included for reference only.) You develop the following code to query the database. (Line numbers are included for reference only.). Question 4: SaveScore will store the values for the gameId and playerId parameters in the database.

![Question 47 part 1](images/question44_45_46_47_1.png)
![Question 47 part 2](images/question44_45_46_47_2.png)
![Question 47 part 3](images/question44_45_46_47_3.jpeg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 1: The code creates an infinite lease.

![Question 48](images/question48_49_50.jpeg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 2: The code at line 06 always creates a new blob.

![Question 49](images/question48_49_50.jpeg)

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution that uses the Azure Storage Client library for .NET. You have the following code: (Line numbers are included for reference only.). Question 3: The finally block releases the lease.

![Question 50](images/question48_49_50.jpeg)

- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are building a website that uses Azure Blob storage for data storage. You configure Azure Blob storage lifecycle to move all blobs to the archive tier after 30 days. Customers have requested a service-level agreement (SLA) for viewing data older than 30 days. You need to document the minimum SLA for data recovery. Which SLA should you use?

- [ ] At least two days.
- [x] Between one and 15 hours.
- [ ] At least one day.
- [ ] Between zero and 60 minutes.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a ticket reservation system for an airline. The storage solution for the application must meet the following requirements: Ensure at least 99.99% availability and provide low latency. Accept reservations even when localized network outages or other unforeseen failures occur. Process reservations in the exact sequence as reservations are submitted to minimize overbooking or selling the same seat to multiple travelers. Allow simultaneous and out-of-order reservations with a maximum five-second tolerance window. You provision a resource group named airlineResourceGroup in the Azure South-Central US region. You need to provision a SQL API Cosmos DB account to support the app. How should you complete the Azure CLI commands?

![Question 52](images/question52.jpeg)

- [x] Box 1: BoundedStaleness. Box 2: --enable-automatic-failover true \. Box 3: --locations 'southcentralplus=0 eastus=1 westus=2'.
- [ ] Box 1: Strong. Box 2: --enable-automatic-failover true \. Box 3: --locations 'southcentralplus=0 eastus=1 westus=2'.
- [ ] Box 1: BoundedStaleness. Box 2: --enable-automatic-failover true \. Box 3: --locations 'southcentralus'.
- [ ] Box 1: Strong. Box 2: --kind 'MongoDB' \. Box 3: --locations 'southcentralus'.

**[⬆ Back to Top](#table-of-contents)**

### You are preparing to deploy a Python website to an Azure Web App using a container. The solution will use multiple containers in the same container group. The Dockerfile that builds the container is as follows. You build a container by using the following command. The Azure Container Registry instance named images is a private registry. The user name and password for the registry is admin. The Web App must always run the same version of the website regardless of future builds. You need to create an Azure Web App to run the website. How should you complete the commands?

![Question 53 part 1](images/question53_1.png)
![Question 53 part 2](images/question53_2.png)
![Question 53 part 3](images/question53_3.jpeg)

- [ ] Box 1: --sku B1 --hyper-v. Box 2: --deployment-source-url images.azurecr.io/website:1.0.0. Box 3: container set --docker-registry-server-url https://images.azurecr.io -u admin -p admin.
- [x] Box 1: --sku B1 --is-linux. Box 2: --deployment-container-image-name images.azurecr.io/website:v1.0.0. Box 3: container set --docker-registry-server-url https://images.azurecr.io -u admin -p admin.
- [ ] Box 1: --tags container. Box 2: --deployment-source-url images.azurecr.io/website:latest. Box 3: set --python-version 2.7 --generic-configurations user=admin password=admin.
- [ ] Box 1: --sku SHARED. Box 2: --deployment-container-image-name images.azurecr.io/website:latest. Box 3: set --python-version 3.6 --generic-configurations user=admin password=admin.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a back-end Azure App Service that scales based on the number of messages contained in a Service Bus queue. A rule already exists to scale up the App Service when the average queue length of unprocessed and valid queue messages is greater than 1000. You need to add a new rule that will continuously scale down the App Service as long as the scale up condition is not met. How should you configure the Scale rule?

![Question 54](images/question54.jpeg)

- [x] Metric source: Service Bus queue. Metric name: Active Message Count. Time train statistic: Average. Operator: Less than or equal to. Operation: Decrease count by.
- [ ] Metric source: Service Bus queue. Metric name: Active Message Count. Time train statistic: Count. Operator: Less than or equal to. Operation: Decrease count by.
- [ ] Metric source: Storage queue. Metric name: Active Message Count. Time train statistic: Count. Operator: Less than. Operation: Decrease count to.
- [ ] Metric source: Service Bus queue. Metric name: Message Count. Time train statistic: Average. Operator: Greater than. Operation: Decrease count to.

**[⬆ Back to Top](#table-of-contents)**

### You have an application that uses Azure Blob storage. You need to update the metadata of the blobs. Which three methods should you use to develop the solution?

![Question 55](images/question55.jpeg)

- [ ] Box 1: Metadata.Add. Box 2: SetMetadataAsync. Box 3: SetPropertiesAsync.
- [ ] Box 1: Metadata.Add. Box 2: SetMetadataAsync. Box 3: UploadFileStream.
- [ ] Box 1: Metadata.Add. Box 2: FetchAttributesAsync. Box 3: SetPropertiesAsync.
- [x] Box 1: FetchAttributesAsync. Box 2: Metadata.Add. Box 3: SetMetadataAsync.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Event Grid. Configure the machine identifier as the partition key and enable capture. Does the solution meet the goal?

- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop Azure solutions. A .NET application needs to receive a message each time an Azure virtual machine finishes processing data. The messages must NOT persist after being processed by the receiving application. You need to implement the .NET object that will receive the messages. Which object should you use?

- [x] QueueClient.
- [ ] SubscriptionClient.
- [ ] TopicClient.
- [ ] CloudQueueClient.

**[⬆ Back to Top](#table-of-contents)**

### You are maintaining an existing application that uses an Azure Blob GPv1 Premium storage account. Data older than three months is rarely used. Data newer than three months must be available immediately. Data older than a year must be saved but does not need to be available immediately. You need to configure the account to support a lifecycle management rule that moves blob data to archive storage for data not modified in the last year. Which three actions should you perform in sequence?

![Question 58](images/question58.jpeg)

- [ ] Box 1: Upgrade the storage account to GPv2. Box 2: Copy the data to be archived to a Standard GPv2 storage account and then delete the data from the original storage account. Box 3: Change the storage account access tier from hot to cool.
- [x] Box 1: Upgrade the storage account to GPv2. Box 2: Create a new GPv2 Standard account and set its default access tier level to cool. Box 3: Copy the data to be archived to a Standard GPv2 storage account and then delete the data from the original storage account.
- [ ] Box 1: Upgrade the storage account to GPv2. Box 2: Copy the data to be archived to a Standard GPv2 storage account and then delete the data from the original storage account. Box 3: Create a new GPv2 Standard account and set its default access tier level to cool.
- [ ] Box 1: Create a new GPv2 Standard account and set its default access tier level to cool. Box 2: Copy the data to be archived to a Standard GPv2 storage account and then delete the data from the original storage account. Box 3: Upgrade the storage account to GPv2.

**[⬆ Back to Top](#table-of-contents)**

### You develop Azure solutions. You must connect to a No-SQL globally-distributed database by using the .NET API. You need to create an object to configure and execute requests in the database. Which code segment should you use?

- [ ] new Container(EndpointUri, PrimaryKey);.
- [ ] new Database(EndpointUri, PrimaryKey);.
- [x] new CosmosClient(EndpointUri, PrimaryKey);.

**[⬆ Back to Top](#table-of-contents)**

### You have an existing Azure storage account that stores large volumes of data across multiple containers. You need to copy all data from the existing storage account to a new storage account. The copy process must meet the following requirements: Automate data movement. Minimize user input required to perform the operation. Ensure that the data movement process is recoverable. What should you use?

- [x] AzCopy.
- [ ] Azure Storage Explorer.
- [ ] Azure portal.
- [ ] .NET Storage Client Library.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web service that will run on Azure virtual machines that use Azure Storage. You configure all virtual machines to use managed identities. You have the following requirements: Secret-based authentication mechanisms are not permitted for accessing an Azure Storage account. Must use only Azure Instance Metadata Service endpoints. You need to write code to retrieve an access token to access Azure Storage.

- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a new page for a website that uses Azure Cosmos DB for data storage. The feature uses documents that have the following format: You must display data for the new page in a specific order. You create the following query for the page: You need to configure a Cosmos DB policy to support the query. How should you configure the policy? To answer, drag the appropriate JSON segments to the correct locations. Each JSON segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**


### You are building a traffic monitoring system that monitors traffic along six highways. The system produces time series analysis-based reports for each highway. Data from traffic sensors are stored in Azure Event Hub. Traffic data is consumed by four departments. Each department has an Azure Web App that displays the time series-based reports and contains a WebJob that processes the incoming data from Event Hub. All Web Apps run on App Service Plans with three instances. Data throughput must be maximized. Latency must be minimized. You need to implement the Azure Event Hub. Which settings should you use? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a microservices solution. You plan to deploy the solution to a multinode Azure Kubernetes Service (AKS) cluster. You need to deploy a solution that includes the following features: reverse proxy capabilities configurable traffic routing TLS termination with a custom certificate Which components should you use? To answer, drag the appropriate components to the correct requirements. Each component may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are implementing an order processing system. A point of sale application publishes orders to topics in an Azure Service Bus queue. The Label property for the topic includes the following data: The system has the following requirements for subscriptions: You need to implement filtering and maximize throughput while evaluating filters. Which filter types should you implement? To answer, drag the appropriate filter types to the correct subscriptions. Each filter type may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Your company has several websites that use a company logo image. You use Azure Content Delivery Network (CDN) to store the static image. You need to determine the correct process of how the CDN and the Point of Presence (POP) server will distribute the image and list the items in the correct order. In which order do the actions occur? To answer, move all actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Cosmos DB solution by using the Azure Cosmos DB SQL API. The data includes millions of documents. Each document may contain hundreds of properties. The properties of the documents do not contain distinct values for partitioning. Azure Cosmos DB must scale individual containers in the database to meet the performance needs of the application by spreading the workload evenly across all partitions over time. You need to select a partition key. Which two partition keys can you use? Each correct answer presents a complete solution.
- [ ] a single property value that does not appear frequently in the documents.
- [ ] a value containing the collection name.
- [ ] a single property value that appears frequently in the documents.
- [x] a concatenation of multiple property values with a random suffix appended.
- [x] a hash suffix appended to a property value.


**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure-hosted e-commerce web application. The application will use Azure Cosmos DB to store sales orders. You are using the latest SDK to manage the sales orders in the database. You create a new Azure Cosmos DB instance. You include a valid endpoint and valid authorization key to an appSettings.json file in the code project. You are evaluating the following application code: (Line number are included for reference only.) For each of the following statements, select Yes if the statement is true. Otherwise, select No.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop an Azure solution that uses Cosmos DB. The current Cosmos DB container must be replicated and must use a partition key that is optimized for queries. You need to implement a change feed processor solution. Which change feed processor components should you use? To answer, drag the appropriate components to the correct requirements. Each component may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view the content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop a web application. You need to register the application with an active Azure Active Directory (Azure AD) tenant. Which three actions should you perform in sequence? To answer, move all actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You have a new Azure subscription. You are developing an internal website for employees to view sensitive data. The website uses Azure Active Directory (Azure AD) for authentication. You need to implement multifactor authentication for the website. Which two actions should you perform? Each correct answer presents part of the solution.
- [ ] Configure the website to use Azure AD B2C.
- [x] In Azure AD, create a new conditional access policy.
- [x] Upgrade to Azure AD Premium.
- [ ] In Azure AD, enable application proxy.
- [ ] In Azure AD conditional access, enable the baseline policy.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a Java application that uses Cassandra to store key and value data. You plan to use a new Azure Cosmos DB resource and the Cassandra API in the application. You create an Azure Active Directory (Azure AD) group named Cosmos DB Creators to enable provisioning of Azure Cosmos accounts, databases, and containers. The Azure AD group must not be able to access the keys that are required to access the data. You need to restrict access to the Azure AD group. Which role-based access control should you use?
- [ ] DocumentDB Accounts Contributor.
- [ ] Cosmos Backup Operator.
- [x] Cosmos DB Operator.
- [ ] Cosmos DB Account Reader.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a website that will run as an Azure Web App. Users will authenticate by using their Azure Active Directory (Azure AD) credentials. You plan to assign users one of the following permission levels for the website: admin, normal, and reader. A user's Azure AD group membership must be used to determine the permission level. You need to configure authorization. Solution: Configure the Azure Web App for the website to allow only authenticated requests and require Azure AD log on. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a website that will run as an Azure Web App. Users will authenticate by using their Azure Active Directory (Azure AD) credentials. You plan to assign users one of the following permission levels for the website: admin, normal, and reader. A user's Azure AD group membership must be used to determine the permission level. You need to configure authorization. Solution: Create a new Azure AD application. In the application's manifest, set value of the groupMembershipClaims option to All. In the website, use the value of the groups claim from the JWT for the user to determine permissions. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a website that will run as an Azure Web App. Users will authenticate by using their Azure Active Directory (Azure AD) credentials. You plan to assign users one of the following permission levels for the website: admin, normal, and reader. A user's Azure AD group membership must be used to determine the permission level. You need to configure authorization. Solution: Create a new Azure AD application. In the application's manifest, define application roles that match the required permission levels for the application. Assign the appropriate Azure AD group to each role. In the website, use the value of the roles claim from the JWT for the user to determine permissions. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application to securely transfer data between on-premises file systems and Azure Blob storage. The application stores keys, secrets, and certificates in Azure Key Vault. The application uses the Azure Key Vault APIs. The application must allow recovery of an accidental deletion of the key vault or key vault objects. Key vault objects must be retained for 90 days after deletion. You need to protect the key vault and key vault objects. Which Azure Key Vault feature should you use? To answer, drag the appropriate features to the correct actions. Each feature may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You provide an Azure API Management managed web service to clients. The back-end web service implements HTTP Strict Transport Security (HSTS). Every request to the backend service must include a valid HTTP authorization header. You need to configure the Azure API Management instance with an authentication policy. Which two policies can you use? Each correct answer presents a complete solution.
- [ ] Basic Authentication.
- [ ] Digest Authentication.
- [x] Certificate Authentication.
- [x] OAuth Client Credential Grant.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an ASP.NET Core website that can be used to manage photographs which are stored in Azure Blob Storage containers. Users of the website authenticate by using their Azure Active Directory (Azure AD) credentials. You implement role-based access control (RBAC) role permissions on the containers that store photographs. You assign users to RBAC roles. You need to configure the website's Azure AD Application so that user's permissions can be used with the Azure Blob containers. How should you configure the application? To answer, drag the appropriate setting to the correct location. Each setting can be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### HOTSPOT -
You are developing an ASP.NET Core app that includes feature flags which are managed by Azure App Configuration. You create an Azure App Configuration store named AppFeatureFlagStore that contains a feature flag named Export. You need to update the app to meet the following requirements: Use the Export feature in the app without requiring a restart of the app. Validate users before users are allowed access to secure resources. Permit users to access secure resources. How should you complete the code segment? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You have an application that includes an Azure Web app and several Azure Function apps. Application secrets including connection strings and certificates are stored in Azure Key Vault. Secrets must not be stored in the application or application runtime environment. Changes to Azure Active Directory (Azure AD) must be minimized. You need to design the approach to loading application secrets. What should you do?
- [ ] Create a single user-assigned Managed Identity with permission to access Key Vault and configure each App Service to use that Managed Identity.
- [ ] Create a single Azure AD Service Principal with permission to access Key Vault and use a client secret from within the App Services to access Key Vault.
- [x] Create a system assigned Managed Identity in each App Service with permission to access Key Vault.
- [ ] Create an Azure AD Service Principal with Permissions to access Key Vault for each App Service and use a certificate from within the App Services to access Key Vault.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a medical records document management website. The website is used to store scanned copies of patient intake forms. If the stored intake forms are downloaded from storage by a third party, the contents of the forms must not be compromised. You need to store the intake forms according to the requirements. Solution: 1. Create an Azure Key Vault key named skey. 2. Encrypt the intake forms using the public key portion of skey. 3. Store the encrypted data in Azure Blob storage. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a medical records document management website. The website is used to store scanned copies of patient intake forms. If the stored intake forms are downloaded from storage by a third party, the contents of the forms must not be compromised. You need to store the intake forms according to the requirements. Solution: 1. Create an Azure Cosmos DB database with Storage Service Encryption enabled. 2. Store the intake forms in the Azure Cosmos DB database. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a medical records document management website. The website is used to store scanned copies of patient intake forms. If the stored intake forms are downloaded from storage by a third party, the contents of the forms must not be compromised. You need to store the intake forms according to the requirements. Solution: Store the intake forms as Azure Key Vault secrets. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You plan to deploy a new application to a Linux virtual machine (VM) that is hosted in Azure. The entire VM must be secured at rest by using industry-standard encryption technology to address organizational security and compliance requirements. You need to configure Azure Disk Encryption for the VM. How should you complete the Azure CLI commands? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**


### Your company is developing an Azure API hosted in Azure. You need to implement authentication for the Azure API to access other Azure resources. You have the following requirements: All API calls must be authenticated. Callers to the API must not send credentials to the API. Which authentication mechanism should you use?
- [ ] Basic.
- [ ] Anonymous.
- [x] Managed identity.
- [ ] Client certificate.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application. You have an Azure user account that has access to two subscriptions. You need to retrieve a storage account key secret from Azure Key Vault. In which order should you arrange the PowerShell commands to develop the solution? To answer, move all commands from the list of commands to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop Azure solutions. You must grant a virtual machine (VM) access to specific resource groups in Azure Resource Manager. You need to obtain an Azure Resource Manager access token. Solution: Use an X.509 certificate to authenticate the VM with Azure Resource Manager. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop Azure solutions. You must grant a virtual machine (VM) access to specific resource groups in Azure Resource Manager. You need to obtain an Azure Resource Manager access token. Solution: Use the Reader role-based access control (RBAC) role to authenticate the VM with Azure Resource Manager. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are building a website that is used to review restaurants. The website will use an Azure CDN to improve performance and add functionality to requests. You build and deploy a mobile app for Apple iPhones. Whenever a user accesses the website from an iPhone, the user must be redirected to the app store. You need to implement an Azure CDN rule that ensures that iPhone users are redirected to the app store. How should you complete the Azure Resource Manager template? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a website that will run as an Azure Web App. Users will authenticate by using their Azure Active Directory (Azure AD) credentials. You plan to assign users one of the following permission levels for the website: admin, normal, and reader. A user's Azure AD group membership must be used to determine the permission level. You need to configure authorization. Solution: Configure and use Integrated Windows Authentication in the website. In the website, query Microsoft Graph API to load the group to which the user is a member. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop Azure solutions. You must grant a virtual machine (VM) access to specific resource groups in Azure Resource Manager. You need to obtain an Azure Resource Manager access token. Solution: Run the Invoke-RestMethod cmdlet to make a request to the local managed identity for Azure resources endpoint. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are building a website to access project data related to teams within your organization. The website does not allow anonymous access. Authentication is performed using an Azure Active Directory (Azure AD) app named internal. The website has the following authentication requirements: Azure AD users must be able to login to the website. Personalization of the website must be based on membership in Active Directory groups. You need to configure the application's manifest to meet the authentication requirements. How should you configure the manifest? To answer, select the appropriate configuration in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop an app that allows users to upload photos and videos to Azure storage. The app uses a storage REST API call to upload the media to a blob storage account named Account1. You have blob storage containers named Container1 and Container2. Uploading of videos occurs on an irregular basis. You need to copy specific blobs from Container1 to Container2 when a new video is uploaded. What should you do?
- [ ] Copy blobs to Container2 by using the Put Blob operation of the Blob Service REST API.
- [x] Create an Event Grid topic that uses the Start-AzureStorageBlobCopy cmdlet.
- [ ] Use AzCopy with the Snapshot switch to copy blobs to Container2.
- [ ] Download the blob to a virtual machine and then upload the blob to Container2.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an ASP.NET Core website that uses Azure FrontDoor. The website is used to build custom weather data sets for researchers. Data sets are downloaded by users as Comma Separated Value (CSV) files. The data is refreshed every 10 hours. Specific files must be purged from the FrontDoor cache based upon Response Header values. You need to purge individual assets from the Front Door cache. Which type of cache purge should you use?
- [x] single path.
- [ ] wildcard.
- [ ] root domain.

**[⬆ Back to Top](#table-of-contents)**

### Your company is developing an Azure API. You need to implement authentication for the Azure API. You have the following requirements: All API calls must be secure. Callers to the API must not send credentials to the API. Which authentication mechanism should you use?
- [ ] Basic.
- [ ] Anonymous.
- [x] Managed identity.
- [ ] Client certificate.

**[⬆ Back to Top](#table-of-contents)**

### You are a developer for a SaaS company that offers many web services. All web services for the company must meet the following requirements: Use API Management to access the services Use OpenID Connect for authentication Prevent anonymous usage A recent security audit found that several web services can be called without any authentication. Which API Management policy should you implement?
- [ ] jsonp.
- [ ] authentication-certificate.
- [ ] check-header.
- [x] validate-jwt.

**[⬆ Back to Top](#table-of-contents)**

### Contoso, Ltd. provides an API to customers by using Azure API Management (APIM). The API authorizes users with a JWT token. You must implement response caching for the APIM gateway. The caching mechanism must detect the user ID of the client that accesses data for a given location and cache the response for that user ID. You need to add the following policies to the policies file: a set-variable policy to store the detected user identity a cache-lookup-value policy a cache-store-value policy a find-and-replace policy to update the response body with the user profile information To which policy section should you add the policies? To answer, drag the appropriate sections to the correct policies. Each section may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution. You need to develop code to access a secret stored in Azure Key Vault. How should you complete the code segment? To answer, drag the appropriate code segments to the correct location. Each code segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure App Service REST API. The API must be called by an Azure App Service web app. The API must retrieve and update user profile information stored in Azure Active Directory (Azure AD). You need to configure the API to make the updates. Which two tools should you use? Each correct answer presents part of the solution.
- [x] Microsoft Graph API.
- [ ] Microsoft Authentication Library (MSAL).
- [x] Azure API Management.
- [ ] Microsoft Azure Security Center.
- [ ] Microsoft Azure Key Vault SDK.

**[⬆ Back to Top](#table-of-contents)**

### You develop a REST API. You implement a user delegation SAS token to communicate with Azure Blob storage. The token is compromised. You need to revoke the token. What are two possible ways to achieve this goal? Each correct answer presents a complete solution.
- [x] Revoke the delegation key.
- [x] Delete the stored access policy.
- [ ] Regenerate the account key.
- [ ] Remove the role assignment for the security principle.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure-hosted application that must use an on-premises hardware security module (HSM) key. The key must be transferred to your existing Azure Key Vault by using the Bring Your Own Key (BYOK) process. You need to securely transfer the key to Azure Key Vault. Which four actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure Logic app that calls an Azure Function app. The Azure Function app includes an OpenAPI (Swagger) definition and uses an Azure Blob storage account. All resources are secured by using Azure Active Directory (Azure AD). The Azure Logic app must securely access the Azure Blob storage account. Azure AD resources must remain if the Azure Logic app is deleted. You need to secure the Azure Logic app. What should you do?
- [ ] Create a user-assigned managed identity and assign role-based access controls.
- [ ] Create an Azure AD custom role and assign the role to the Azure Blob storage account.
- [x] Create an Azure Key Vault and issue a client certificate.
- [x] Create a system-assigned managed identity and issue a client certificate.
- [ ] Create an Azure AD custom role and assign role-based access controls.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that uses a premium block blob storage account. You are optimizing costs by automating Azure Blob Storage access tiers. You apply the following policy rules to the storage account. You must determine the implications of applying the rules to the data. (Line numbers are included for reference only.) For each of the following statements, select Yes if the statement is true. Otherwise, select No.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution that will use a multi-partitioned Azure Cosmos DB database. You plan to use the latest Azure Cosmos DB SDK for development. The solution must meet the following requirements: Send insert and update operations to an Azure Blob storage account. Process changes to all partitions immediately. Allow parallelization of change processing. You need to process the Azure Cosmos DB operations. What are two possible ways to achieve this goal? Each correct answer presents a complete solution.
- [ ] Create an Azure App Service API and implement the change feed estimator of the SDK. Scale the API by using multiple Azure App Service instances.
- [ ] Create a background job in an Azure Kubernetes Service and implement the change feed feature of the SDK.
- [ ] Create an Azure Function to use a trigger for Azure Cosmos DB. Configure the trigger to connect to the container.
- [ ] Create an Azure Function that uses a FeedIterator object that processes the change feed by using the pull model on the container. Use a FeedRange objext to parallelize the processing of the change feed across multiple functions.

**[⬆ Back to Top](#table-of-contents)**

### You have an Azure Web app that uses Cosmos DB as a data store. You create a CosmosDB container by running the following PowerShell script: $resourceGroupName = "testResourceGroup" $accountName = "testCosmosAccount" $databaseName = "testDatabase" $containerName = "testContainer" $partitionKeyPath = "/EmployeeId" $autoscaleMaxThroughput = 5000 New-AzCosmosDBSqlContainer - -ResourceGroupName $resourceGroupName -AccountName $accountName -DatabaseName $databaseName -Name $containerName -PartitionKeyKind Hash -PartitionKeyPath $partitionKeyPath -AutoscaleMaxThroughput $autoscaleMaxThroughput You create the following queries that target the container: SELECT * FROM c WHERE c.EmployeeId > '12345' SELECT * FROM c WHERE c.UserID = '12345' For each of the following statements, select Yes if the statement is true. Otherwise, select No.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web application that makes calls to the Microsoft Graph API. You register the application in the Azure portal and upload a valid X509 certificate. You create an appsettings.json file containing the certificate name, client identifier for the application, and the tenant identifier of the Azure Active Directory (Azure AD). You create a method named ReadCertificate to return the X509 certificate by name. You need to implement code that acquires a token by using the certificate. How should you complete the code segment? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an ASP.NET Core Web API web service. The web service uses Azure Application Insights for all telemetry and dependency tracking. The web service reads and writes data to a database other than Microsoft SQL Server. You need to ensure that dependency tracking works for calls to the third-party database. Which two dependency telemetry properties should you use? Each correct answer presents part of the solution.
- [ ] Telemetry.Context.Cloud.RoleInstance.
- [ ] Telemetry.Id.
- [ ] Telemetry.Name.
- [ ] Telemetry.Context.Operation.Id.
- [ ] Telemetry.Context.Session.Id.

**[⬆ Back to Top](#table-of-contents)**

### You are using Azure Front Door Service. You are expecting inbound files to be compressed by using Brotli compression. You discover that inbound XML files are not compressed. The files are 9 megabytes (MB) in size. You need to determine the root cause for the issue. To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure App Service hosted ASP.NET Core web app to deliver video-on-demand streaming media. You enable an Azure Content Delivery Network (CDN) Standard for the web endpoint. Customer videos are downloaded from the web app by using the following example URL: http://www.contoso.com/ content.mp4?quality=1 All media content must expire from the cache after one hour. Customer videos with varying quality must be delivered to the closest regional point of presence (POP) node. You need to configure Azure CDN caching rules. Which options should you use? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop a web app that uses tier D1 app service plan by using the Web Apps feature of Microsoft Azure App Service. Spikes in traffic have caused increases in page load times. You need to ensure that the web app automatically scales when CPU load is about 85 percent and minimize costs. Which four actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. NOTE: More than one order of answer choices is correct. You will receive credit for any of the correct orders you select. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Determine whether the solution meets the stated goals. You are developing and deploying several ASP.NET web applications to Azure App Service. You plan to save session state information and HTML output. You must use a storage mechanism with the following requirements: Share session state across all ASP.NET web applications. Support controlled, concurrent access to the same session state data for multiple readers and a single writer. Save full HTTP responses for concurrent requests. You need to store the information. Proposed Solution: Enable Application Request Routing (ARR). Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Determine whether the solution meets the stated goals. You are developing and deploying several ASP.NET web applications to Azure App Service. You plan to save session state information and HTML output. You must use a storage mechanism with the following requirements: Share session state across all ASP.NET web applications. Support controlled, concurrent access to the same session state data for multiple readers and a single writer. Save full HTTP responses for concurrent requests. You need to store the information. Proposed Solution: Deploy and configure an Azure Database for PostgreSQL. Update the web applications. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### A company is developing a gaming platform. Users can join teams to play online and see leaderboards that include player statistics. The solution includes an entity named Team. You plan to implement an Azure Redis Cache instance to improve the efficiency of data operations for entities that rarely change. You need to invalidate the cache when team data is changed. How should you complete the code? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### A company has multiple warehouses. Each warehouse contains IoT temperature devices which deliver temperature data to an Azure Service Bus queue. You need to send email alerts to facility supervisors immediately if the temperature at a warehouse goes above or below specified threshold temperatures. Which five actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop an ASP.NET Core MVC application. You configure the application to track webpages and custom events. You need to identify trends in application usage. Which Azure Application Insights Usage Analysis features should you use? To answer, drag the appropriate features to the correct requirements. Each feature may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop a gateway solution for a public facing news API. The news API back end is implemented as a RESTful service and uses an OpenAPI specification. You need to ensure that you can access the news API by using an Azure API Management service instance. Which Azure PowerShell command should you run?
- [x] Import-AzureRmApiManagementApi -Context $ApiMgmtContext -SpecificationFormat "Swagger" -SpecificationPath $SwaggerPath -Path $Path.
- [ ] New-AzureRmApiManagementBackend -Context $ApiMgmtContext-Url $Url -Protocol http.
- [ ] New-AzureRmApiManagement -ResourceGroupName $ResourceGroup -Name $Name ג€"Location $Location -Organization $Org -AdminEmail $AdminEmail.
- [ ] New-AzureRmApiManagementBackendProxy -Url $ApiUrl.

**[⬆ Back to Top](#table-of-contents)**

### You are creating a hazard notification system that has a single signaling server which triggers audio and visual alarms to start and stop. You implement Azure Service Bus to publish alarms. Each alarm controller uses Azure Service Bus to receive alarm signals as part of a transaction. Alarm events must be recorded for audit purposes. Each transaction record must include information about the alarm type that was activated. You need to implement a reply trail auditing solution. Which two actions should you perform? Each correct answer resents part of the solution.
- [ ] Assign the value of the hazard message SessionID property to the ReplyToSessionId property.
- [x] Assign the value of the hazard message MessageId property to the DevileryCount property.
- [ ] Assign the value of the hazard message SessionID property to the SequenceNumber property.
- [ ] Assign the value of the hazard message MessageId property to the CorrelationId property.
- [ ] Assign the value of the hazard message SequenceNumber property to the DeliveryCount property.
- [ ] Assign the value of the hazard message MessageId property to the SequenceNumber property.



**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure function that connects to an Azure SQL Database instance. The function is triggered by an Azure Storage queue. You receive reports of numerous System.InvalidOperationExceptions with the following message: ג€Timeout expired. The timeout period elapsed prior to obtaining a connection from the pool. This may have occurred because all pooled connections were in use and max pool size was reached.ג€ You need to prevent the exception. What should you do?
- [ ] In the host.json file, decrease the value of the batchSize option.
- [ ] Convert the trigger to Azure Event Hub.
- [x] Convert the Azure Function to the Premium plan.
- [ ] In the function.json file, change the value of the type option to queueScaling.

**[⬆ Back to Top](#table-of-contents)**

### Determine whether the solution meets the stated goals. You are developing and deploying several ASP.NET web applications to Azure App Service. You plan to save session state information and HTML output. You must use a storage mechanism with the following requirements: Share session state across all ASP.NET web applications. Support controlled, concurrent access to the same session state data for multiple readers and a single writer. Save full HTTP responses for concurrent requests. You need to store the information. Proposed Solution: Deploy and configure Azure Cache for Redis. Update the web applications. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are debugging an application that is running on Azure Kubernetes cluster named cluster1. The cluster uses Azure Monitor for containers to monitor the cluster. The application has sticky sessions enabled on the ingress controller. Some customers report a large number of errors in the application over the last 24 hours. You need to determine on which virtual machines (VMs) the errors are occurring. How should you complete the Azure Monitor query? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You plan to deploy a web app to App Service on Linux. You create an App Service plan. You create and push a custom Docker image that contains the web app to Azure Container Registry. You need to access the console logs generated from inside the container in real-time. How should you complete the Azure CLI command? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an ASP.NET web app to Azure App Service. You use Application Insights telemetry to monitor the app. You must test the app to ensure that the app is available and responsive from various points around the world and at regular intervals. If the app is not responding, you must send an alert to support staff. You need to configure a test for the web app. Which two test types can you use? Each correct answer presents a complete solution.
- [ ] integration.
- [x] multi-step web.
- [x] URL ping.
- [ ] unit.
- [ ] load.

**[⬆ Back to Top](#table-of-contents)**

### A web service provides customer summary information for e-commerce partners. The web service is implemented as an Azure Function app with an HTTP trigger. Access to the API is provided by an Azure API Management instance. The API Management instance is configured in consumption plan mode. All API calls are authenticated by using OAuth. API calls must be cached. Customers must not be able to view cached data for other customers. You need to configure API Management policies for caching. How should you complete the policy statement? Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing applications for a company. You plan to host the applications on Azure App Services. The company has the following requirements: Every five minutes verify that the websites are responsive. Verify that the websites respond within a specified time threshold. Dependent requests such as images and JavaScript files must load properly. Generate alerts if a website is experiencing issues. If a website fails to load, the system must attempt to reload the site three more times. You need to implement this process with the least amount of effort. What should you do?
- [ ] Create a Selenium web test and configure it to run from your workstation as a scheduled task.
- [ ] Set up a URL ping test to query the home page.
- [ ] Create an Azure function to query the home page.
- [x] Create a multi-step web test to query the home page.
- [ ] Create a Custom Track Availability Test to query the home page.

**[⬆ Back to Top](#table-of-contents)**

### You develop and add several functions to an Azure Function app that uses the latest runtime host. The functions contain several REST API endpoints secured by using SSL. The Azure Function app runs in a Consumption plan. You must send an alert when any of the function endpoints are unavailable or responding too slowly. You need to monitor the availability and responsiveness of the functions. What should you do?
- [ ] Create a URL ping test.
- [x] Create a timer triggered function that calls TrackAvailability() and send the results to Application Insights.
- [ ] Create a timer triggered function that calls GetMetric("Request Size") and send the results to Application Insights.
- [ ] Add a new diagnostic setting to the Azure Function app. Enable the FunctionAppLogs and Send to Log Analytics options.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application to retrieve user profile information. The application will use the Microsoft Graph SDK. The app must retrieve user profile information by using a Microsoft Graph API call. You need to call the Microsoft Graph API from the application. In which order should you perform the actions? To answer, move all actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop and deploy an Azure Logic App that calls an Azure Function app. The Azure Function App includes an OpenAPI (Swagger) definition and uses an Azure Blob storage account. All resources are secured by using Azure Active Directory (Azure AD). The Logic App must use Azure Monitor logs to record and store information about runtime data and events. The logs must be stored in the Azure Blob storage account. You need to set up Azure Monitor logs and collect diagnostics data for the Azure Logic App. Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop an application. You plan to host the application on a set of virtual machines (VMs) in Azure. You need to configure Azure Monitor to collect logs from the application. Which four actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You have an application that provides weather forecasting data to external partners. You use Azure API Management to publish APIs. You must change the behavior of the API to meet the following requirements: Support alternative input parameters Remove formatting text from responses Provide additional context to back-end services Which types of policies should you implement? To answer, drag the policy types to the correct scenarios. Each policy type may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an e-commerce solution that uses a microservice architecture. You need to design a communication backplane for communicating transactional messages between various parts of the solution. Messages must be communicated in first-in-first-out (FIFO) order. What should you use?
- [x] Azure Storage Queue.
- [ ] Azure Event Hub.
- [ ] Azure Service Bus.
- [ ] Azure Event Grid.

**[⬆ Back to Top](#table-of-contents)**

### A company backs up all manufacturing data to Azure Blob Storage. Admins move blobs from hot storage to archive tier storage every month. You must automatically move blobs to Archive tier after they have not been modified within 180 days. The path for any item that is not archived must be placed in an existing queue. This operation must be performed automatically once a month. You set the value of TierAgeInDays to -180. How should you configure the Logic App? To answer, drag the appropriate triggers or action blocks to the correct trigger or action slots. Each trigger or action block may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Service application that processes queue data when it receives a message from a mobile application. Messages may not be sent to the service consistently. You have the following requirements: Queue size must not grow larger than 80 gigabytes (GB). Use first-in-first-out (FIFO) ordering of messages. Minimize Azure costs. You need to implement the messaging solution. Solution: Use the .Net API to add a message to an Azure Service Bus Queue from the mobile application. Create an Azure Function App that uses an Azure Service Bus Queue trigger. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Notification Hub. Register all devices with the hub. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Service Bus. Configure a topic to receive the device data by using a correlation filter. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Event Grid. Configure event filtering to evaluate the device identifier. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You manage several existing Logic Apps. You need to change definitions, add new logic, and optimize these apps on a regular basis. What should you use? To answer, drag the appropriate tools to the correct functionalities. Each tool may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### A company is developing a solution that allows smart refrigerators to send temperature information to a central location. The solution must receive and store messages until they can be processed. You create an Azure Service Bus instance by providing a name, pricing tier, subscription, resource group, and location. You need to complete the configuration. Which Azure CLI or PowerShell command should you run?
- [x] A.
- [ ] B.
- [ ] C.
- [ ] D.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that uses Azure Storage Queues. You have the following code: For each of the following statements, select Yes if the statement is true. Otherwise, select No.

- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### A company is developing a solution that allows smart refrigerators to send temperature information to a central location. The solution must receive and store messages until they can be processed. You create an Azure Service Bus instance by providing a name, pricing tier, subscription, resource group, and location. You need to complete the configuration. Which Azure CLI or PowerShell command should you run?
- [ ] A.
- [ ] B.
- [x] C.
- [ ] D.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Service application that processes queue data when it receives a message from a mobile application. Messages may not be sent to the service consistently. You have the following requirements: Queue size must not grow larger than 80 gigabytes (GB). Use first-in-first-out (FIFO) ordering of messages. Minimize Azure costs. You need to implement the messaging solution. Solution: Use the .Net API to add a message to an Azure Storage Queue from the mobile application. Create an Azure Function App that uses an Azure Storage Queue trigger. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop software solutions for a mobile delivery service. You are developing a mobile app that users can use to order from a restaurant in their area. The app uses the following workflow: 1. A driver selects the restaurants for which they will deliver orders. 2. Orders are sent to all available drivers in an area. 3. Only orders for the selected restaurants will appear for the driver. 4. The first driver to accept an order removes it from the list of available orders. You need to implement an Azure Service Bus solution. Which three actions should you perform in sequence? To answer, move the appropriate actions from the list of actions to the answer area and arrange them in the correct order. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You develop a news and blog content app for Windows devices. A notification must arrive on a user's device when there is a new article available for them to view. You need to implement push notifications. How should you complete the code segment? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure messaging solution. You need to ensure that the solution meets the following requirements: Provide transactional support. Provide duplicate detection. Store the messages for an unlimited period of time. Which two technologies will meet the requirements? Each correct answer presents a complete solution.
- [x] Azure Service Bus Topic.
- [x] Azure Service Bus Queue.
- [ ] Azure Storage Queue.
- [ ] Azure Event Hub.

**[⬆ Back to Top](#table-of-contents)**

### You develop a gateway solution for a public facing news API. The news API back end is implemented as a RESTful service and hosted in an Azure App Service instance. You need to configure back-end authentication for the API Management service instance. Which target and gateway credential type should you use? To answer, drag the appropriate values to the correct parameters. Each value may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are creating an app that uses Event Grid to connect with other services. Your app's event data will be sent to a serverless function that checks compliance. This function is maintained by your company. You write a new event subscription at the scope of your resource. The event must be invalidated after a specific period of time. You need to configure Event Grid. What should you do? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are working for Contoso, Ltd. You define an API Policy object by using the following XML markup: For each of the following statements, select Yes if the statement is true. Otherwise, select No.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution that will use Azure messaging services. You need to ensure that the solution uses a publish-subscribe model and eliminates the need for constant polling. What are two possible ways to achieve the goal? Each correct answer presents a complete solution.
- [ ] Service Bus.
- [ ] Event Hub.
- [ ] Event Grid.
- [ ] Queue.

**[⬆ Back to Top](#table-of-contents)**

### A company is implementing a publish-subscribe (Pub/Sub) messaging component by using Azure Service Bus. You are developing the first subscription application. In the Azure portal you see that messages are being sent to the subscription for each topic. You create and initialize a subscription client object by supplying the correct details, but the subscription application is still not consuming the messages. You need to ensure that the subscription client processes all messages. Which code segment should you use?
- [ ] await subscriptionClient.AddRuleAsync(new RuleDescription(RuleDescription.DefaultRuleName, new TrueFilter()));.
- [ ] subscriptionClient = new SubscriptionClient(ServiceBusConnectionString, TopicName, SubscriptionName);.
- [ ] await subscriptionClient.CloseAsync();.
- [ ] subscriptionClient.RegisterMessageHandler(ProcessMessagesAsync, messageHandlerOptions);.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Service application that processes queue data when it receives a message from a mobile application. Messages may not be sent to the service consistently. You have the following requirements: Queue size must not grow larger than 80 gigabytes (GB). Use first-in-first-out (FIFO) ordering of messages. Minimize Azure costs. You need to implement the messaging solution. Solution: Use the .Net API to add a message to an Azure Storage Queue from the mobile application. Create an Azure VM that is triggered from Azure Storage Queue events. Does the solution meet the goal?
- [ ] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure Service application that processes queue data when it receives a message from a mobile application. Messages may not be sent to the service consistently. You have the following requirements: Queue size must not grow larger than 80 gigabytes (GB). Use first-in-first-out (FIFO) ordering of messages. Minimize Azure costs. You need to implement the messaging solution. Solution: Use the .Net API to add a message to an Azure Service Bus Queue from the mobile application. Create an Azure Windows VM that is triggered from Azure Service Bus Queue. Does the solution meet the goal?
- [ ] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a REST web service. Customers will access the service by using an Azure API Management instance. The web service does not correctly handle conflicts. Instead of returning an HTTP status code of 409, the service returns a status code of 500. The body of the status message contains only the word conflict. You need to ensure that conflicts produce the correct response. How should you complete the policy? To answer, drag the appropriate code segments to the correct locations. Each code segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are a developer for a Software as a Service (SaaS) company. You develop solutions that provide the ability to send notifications by using Azure Notification Hubs. You need to create sample code that customers can use as a reference for how to send raw notifications to Windows Push Notification Services (WNS) devices. The sample code must not use external packages. How should you complete the code segment? To answer, drag the appropriate code segments to the correct locations. Each code segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Event Hub. Configure the machine identifier as the partition key and enable capture. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect inventory data from thousands of stores located around the world. Each store location will send the inventory data hourly to an Azure Blob storage account for processing. The solution must meet the following requirements: Begin processing when data is saved to Azure Blob storage. Filter data based on store location information. Trigger an Azure Logic App to process the data for output to Azure Cosmos DB. Enable high availability and geographic distribution. Allow 24-hours for retries. Implement an exponential back off data processing. You need to configure the solution. What should you implement? To answer, select the appropriate options in the answer area. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Container blade. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a REST web service. Customers will access the service by using an Azure API Management instance. The web service does not correctly handle conflicts. Instead of returning an HTTP status code of 409, the service returns a status code of 500. The body of the status message contains only the word conflict. You need to ensure that conflicts produce the correct response. How should you complete the policy? To answer, drag the appropriate code segments to the correct locations. Each code segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are a developer for a Software as a Service (SaaS) company. You develop solutions that provide the ability to send notifications by using Azure Notification Hubs. You need to create sample code that customers can use as a reference for how to send raw notifications to Windows Push Notification Services (WNS) devices. The sample code must not use external packages. How should you complete the code segment? To answer, drag the appropriate code segments to the correct locations. Each code segment may be used once, more than once, or not at all. You may need to drag the split bar between panes or scroll to view content. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### You are developing an Azure solution to collect point-of-sale (POS) device data from 2,000 stores located throughout the world. A single device can produce 2 megabytes (MB) of data every 24 hours. Each store location has one to five devices that send data. You must store the device data in Azure Blob storage. Device data must be correlated based on a device identifier. Additional stores are expected to open in the future. You need to implement a solution to receive the device data. Solution: Provision an Azure Event Hub. Configure the machine identifier as the partition key and enable capture. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### DRAG DROP -
You are developing an Azure solution to collect inventory data from thousands of stores located around the world. Each store location will send the inventory data hourly to an Azure Blob storage account for processing. The solution must meet the following requirements: Begin processing when data is saved to Azure Blob storage. Filter data based on store location information. Trigger an Azure Logic App to process the data for output to Azure Cosmos DB. Enable high availability and geographic distribution. Allow 24-hours for retries. Implement an exponential back off data processing. You need to configure the solution. What should you implement? To answer, select the appropriate options in the answer area. Select and Place:
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Container blade. Does the solution meet the goal?
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Container blade. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Container blade. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You open the Azure Application Gateway's HTTP setting and set the Override backend path option to mywebapp1.azurewebsites.net. You then enable the Use for App service option. Does this meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You configure mywebapp1 to run in an Azure App service environment (ASE). Does this meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You open the Azure Application Gateway's HTTP setting and set the Override backend path option to mywebapp1.azurewebsites.net. You then add an authentication certificate for mywebapp1.azurewebsites.net. Does t is meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a web app named WebApp1. You use the WebJobs SDK to design a triggered App Service background task that automatically invokes a function in the code every time new data is received in a queue. You are preparing to configure the service processes a queue data item. Which of the following is the service you should use?
- [ ] Logic Apps.
- [x] WebJobs.
- [ ] Flow.
- [ ] Functions.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure subscription. You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set. You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance. Which of the following is the value that you should configure for the platformFaultDomainCount property?
- [ ] 10.
- [ ] 30.
- [ ] Min Value.
- [x] Max Value.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Container blade. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an azure subscription that includes a storage account, a resource group, a blob container and a file share. A fellow administrator named Jon Ross used an Azure Resource Manager template to deploy a virtual machine and an Azure Storage account. You need to identify the Azure Resource Manager template the Jon Ross used. Solution: You access the Resource Group blade. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You have two Hyper-V hosts named Host1 and Host2. Host1 has an Azure virtual machine named VM1 that was deployed by using a custom Azure Resource Manager template. You need to move VM1 to Host2. What should you do?
- [ ] From the Update management blade, click Enable.
- [ ] From the Overview blade, move VM1 to a different subscription.
- [ ] From the Redeploy blade, click Redeploy.
- [ ] From the Profile blade, modify the usage location.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure Kubernetes Service (AKS) cluster that you manage from an Azure AD-joined device. The cluster is located in a resource group. Developers have created an application named MyApp. MyApp was packaged into a container image. You need to deploy the YAML manifest file for the application. Solution: You install the Azure CLI on the device and run the kubectl apply `"f myapp.yaml command. Does this meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure Kubernetes Service (AKS) cluster that you manage from an Azure AD-joined device. The cluster is located in a resource group. Developers have created an application named MyApp. MyApp was packaged into a container image. You need to deploy the YAML manifest file for the application. Solution: You install the docker client on the device and run the docker run -it microsoft/azure-cli:0.10.17 command. Does this meet the goal?
- [ ] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You open the Azure Application Gateway's HTTP setting and set the Override backend path option to mywebapp1.azurewebsites.net. You then enable the Use for App service option. Does this meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You configure mywebapp1 to run in an Azure App service environment (ASE). Does this meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app named mywebapp1. Mywebapp1 uses the address myapp1.azurewebsites.net. You protect mywebapp1 by implementing an Azure Web Application Firewall (WAF). The traffic to mywebapp1 is routed through an Azure Application Gateway instance that is also used by other web apps. You want to secure all traffic to mywebapp1 by using SSL. Solution: You open the Azure Application Gateway's HTTP setting and set the Override backend path option to mywebapp1.azurewebsites.net. You then add an authentication certificate for mywebapp1.azurewebsites.net. Does this meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has a web app named WebApp1. You use the WebJobs SDK to design a triggered App Service background task that automatically invokes a function in the code every time new data is received in a queue. You are preparing to configure the service processes a queue data item. Which of the following is the service you should use?
- [ ] Logic Apps.
- [x] WebJobs.
- [ ] Flow.
- [ ] Functions.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure subscription. You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set. You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance. Which of the following is the value that you should configure for the platformFaultDomainCount property?
- [ ] 10.
- [ ] 30.
- [x] Min Value.
- [ ] Max Value.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure subscription. You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set. You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance. Which of the following is the value that you should configure for the platformUpdateDomainCount property?
- [ ] 10.
- [ ] 20.
- [ ] 30.
- [x] 40.

**[⬆ Back to Top](#table-of-contents)**

### You are designing an Azure WebJob that will run on the same instances as a web app. You want to make use of a suitable WebJob type. The webjob type should also allow for the option to restrict the WebJob to a single instance. Solution: You configure the use of the Triggered WebJob type. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are designing an Azure WebJob that will run on the same instances as a web app. You want to make use of a suitable WebJob type. The webjob type should also allow for the option to restrict the WebJob to a single instance. Solution: You configure the use of the Continuous WebJob type. Does the solution meet the goal?
- [ ] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**


### This question requires that you evaluate the underlined text to determine if it is correct. You company has an on-premises deployment of MongoDB, and an Azure Cosmos DB account that makes use of the MongoDB API. You need to devise a strategy to migrate MongoDB to the Azure Cosmos DB account. You include the Data Management Gateway tool in your migration strategy. Instructions: Review the underlined text. If it makes the statement correct, select `No change required.` If the statement is incorrect, select the answer choice that makes the statement correct.
- [ ] No change required.
- [x] mongorestore.
- [ ] Azure Storage Explorer.
- [ ] AzCopy.


**[⬆ Back to Top](#table-of-contents)**


### You are developing an application that processes Azure Blob storage events. Your application has the following requirements: Process transaction logs asynchronously for changes that occur to the blobs and the blob metadata. Process changes in the order in which they occurred. Retain changes for compliance reasons. Solution: You use Azure Event Grid with a subscriber Azure Function app. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure subscription. You need to deploy a number of Azure virtual machines to the subscription by using Azure Resource Manager (ARM) templates. The virtual machines will be included in a single availability set. You need to ensure that the ARM template allows for as many virtual machines as possible to remain accessible in the event of fabric failure or maintenance. Which of the following is the value that you should configure for the platformUpdateDomainCount property?
- [ ] 10.
- [ ] 20.
- [ ] 30.
- [x] 40.

**[⬆ Back to Top](#table-of-contents)**

### You are designing an Azure WebJob that will run on the same instances as a web app. You want to make use of a suitable WebJob type. The webjob type should also allow for the option to restrict the WebJob to a single instance. Solution: You configure the use of the Triggered WebJob type. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are designing an Azure WebJob that will run on the same instances as a web app. You want to make use of a suitable WebJob type. The webjob type should also allow for the option to restrict the WebJob to a single instance. Solution: You configure the use of the Continuous WebJob type. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### This question requires that you evaluate the underlined text to determine if it is correct. You company has an on-premises deployment of MongoDB, and an Azure Cosmos DB account that makes use of the MongoDB API. You need to devise a strategy to migrate MongoDB to the Azure Cosmos DB account. You include the Data Management Gateway tool in your migration strategy. Instructions: Review the underlined text. If it makes the statement correct, select `No change required.` If the statement is incorrect, select the answer choice that makes the statement correct.
- [ ] No change required.
- [x] mongorestore.
- [ ] Azure Storage Explorer.
- [ ] AzCopy.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that processes Azure Blob storage events. Your application has the following requirements: Process transaction logs asynchronously for changes that occur to the blobs and the blob metadata. Process changes in the order in which they occurred. Retain changes for compliance reasons. Solution: You use Azure Event Grid with a subscriber Azure Function app. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that processes Azure Blob storage events. Your application has the following requirements: Process transaction logs asynchronously for changes that occur to the blobs and the blob metadata. Process changes in the order in which they occurred. Retain changes for compliance reasons. Solution: You use Azure Monitor HTTP Data Collector API. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a mobile app that uses an Azure SQL Database named Weyland. The database contains a table names Customers that has a field named email_address. You want to implement dynamic data masking to hide the data in the email_address field. Solution: You run the follows transact-SQL statement: ALTER TABLE [dbo].[Weyland].[Customers] ALTER COLUMN [email_address] ADD MASKED WITH (FUNCTION = 'email()') Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a mobile app that uses an Azure SQL Database named Weyland. The database contains a table names Customers that has a field named email_address. You want to implement dynamic data masking to hide the data in the email_address field. Solution: You run the Set-AzSqlDatabaseDataMaskingPolicy -DatabaseName "Weyland" Powershell cmdlet Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a mobile app that uses an Azure SQL Database named Weyland. The database contains a table names Customers that has a field named email_address. You want to implement dynamic data masking to hide the data in the email_address field. Solution: You run the Set-AzSqlDatabaseDataMaskingRule -DatabaseName "Weyland" -SchemaName "dbo" -TableName "Customers" -ColumnName "email_address" -MaskingFunction "email" Powershell cmdlet Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an e-Commerce Web App. You want to use Azure Key Vault to ensure that sign-ins to the e-Commerce Web App are secured by using Azure App Service authentication and Azure Active Directory (AAD). What should you do on the e-Commerce Web App?
- [ ] Run the az keyvault secret command.
- [ ] Enable Azure AD Connect.
- [x] Enable Managed Service Identity (MSI).
- [ ] Create an Azure AD service principal.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a web app that uses Azure Active Directory (Azure AD) for authentication. You want to configure the web app to use multifactor authentication. What should you do?
- [ ] Enable mobile app authentication.
- [ ] In Azure AD conditional access, enable the baseline policy.
- [x] In Azure AD, create a conditional access policy.
- [ ] Install the Azure Multi-Factor Authentication Server.

**[⬆ Back to Top](#table-of-contents)**

### This question requires that you evaluate the underlined text to determine if it is correct. Your Azure Active Directory Azure (Azure AD) tenant has an Azure subscription linked to it. Your developer has created a mobile application that obtains Azure AD access tokens using the OAuth 2 implicit grant type. The mobile application must be registered in Azure AD. You require a redirect URI from the developer for registration purposes. Instructions: Review the underlined text. If it makes the statement correct, select `No change is needed.` If the statement is incorrect, select the answer choice that makes the statement correct.
- [x] No change required.
- [ ] a secret.
- [ ] a login hint.
- [ ] a client ID.

**[⬆ Back to Top](#table-of-contents)**

### You are creating an Azure key vault using PowerShell. Objects deleted from the key vault must be kept for a set period of 90 days. Which two of the following parameters must be used in conjunction to meet the requirement? (Choose two.)
- [ ] EnabledForDeployment.
- [x] EnablePurgeProtection.
- [ ] EnabledForTemplateDeployment.
- [ ] EnableSoftDelete.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure Active Directory (Azure AD) environment. Users occasionally connect to Azure AD via the Internet. You need to ensure that users who connect to Azure AD via the internet using an unidentified IP address, are automatically instructed to change their passwords. Solution: You configure the use of Azure Key Vault. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure Active Directory (Azure AD) environment. Users occasionally connect to Azure AD via the Internet. You need to ensure that users who connect to Azure AD via the internet using an unidentified IP address, are automatically instructed to change their passwords. Solution: You configure the use of Azure AD Identity Protection. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### Your company has an Azure Active Directory (Azure AD) environment. Users occasionally connect to Azure AD via the Internet. You need to ensure that users who connect to Azure AD via the internet using an unidentified IP address, are automatically instructed to change their passwords. Solution: You configure the use of Azure AD Privileged Identity Management. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You manage an Azure SQL database that allows for Azure AD authentication. You need to make sure that database developers can connect to the SQL database via Microsoft SQL Server Management Studio (SSMS). You also need to make sure the developers use their on-premises Active Directory account for authentication. Your strategy should allow for authentication prompts to be kept to a minimum. Which of the following should you implement?
- [ ] Azure AD token.
- [ ] Azure Multi-Factor authentication.
- [x] Active Directory integrated authentication.
- [ ] OATH software tokens.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application to transfer data between on-premises file servers and Azure Blob storage. The application stores keys, secrets, and certificates in Azure Key Vault and makes use of the Azure Key Vault APIs. You want to configure the application to allow recovery of an accidental deletion of the key vault or key vault objects for 90 days after deletion. What should you do?
- [ ] Run the Add-AzKeyVaultKey cmdlet.
- [ ] Run the az keyvault update --enable-soft-delete true --enable-purge-protection true CLI.
- [ ] Implement virtual network service endpoints for Azure Key Vault.
- [x] Run the az keyvault update --enable-soft-delete false CLI.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment. You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user. Solution: You include the use of Azure Redis Cache in your design. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment. You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user. Solution: You include the use of an Azure Content Delivery Network (CDN) in your design. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are configuring a web app that delivers streaming video to users. The application makes use of continuous integration and deployment. You need to ensure that the application is highly available and that the users' streaming experience is constant. You also want to configure the application to store data in a geographic location that is nearest to the user. Solution: You include the use of a Storage Area Network (SAN) in your design. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You develop a Web App on a tier D1 app service plan. You notice that page load times increase during periods of peak traffic. You want to implement automatic scaling when CPU load is above 80 percent. Your solution must minimize costs. What should you do first?
- [ ] Enable autoscaling on the Web App.
- [ ] Switch to the Premium App Service tier plan.
- [x] Switch to the Standard App Service tier plan.
- [ ] Switch to the Azure App Services consumption plan.

**[⬆ Back to Top](#table-of-contents)**

### Your company's Azure subscription includes an Azure Log Analytics workspace. Your company has a hundred on-premises servers that run either Windows Server 2012 R2 or Windows Server 2016, and is linked to the Azure Log Analytics workspace. The Azure Log Analytics workspace is set up to gather performance counters associated with security from these linked servers. You must configure alerts based on the information gathered by the Azure Log Analytics workspace. You have to make sure that alert rules allow for dimensions, and that alert creation time should be kept to a minimum. Furthermore, a single alert notification must be created when the alert is created and when the alert is resolved. You need to make use of the necessary signal type when creating the alert rules. Which of the following is the option you should use?
- [ ] The Activity log signal type.
- [ ] The Application Log signal type.
- [x] The Metric signal type.
- [ ] The Audit Log signal type.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a .NET Core MVC application that allows customers to research independent holiday accommodation providers. You want to implement Azure Search to allow the application to search the index by using various criteria to locate documents related to accommodation. You want the application to allow customers to search the index by using regular expressions. What should you do?
- [ ] Configure the SearchMode property of the SearchParameters class.
- [x] Configure the QueryType property of the SearchParameters class.
- [ ] Configure the Facets property of the SearchParameters class.
- [ ] Configure the Filter property of the SearchParameters class.

**[⬆ Back to Top](#table-of-contents)**

### You are a developer at your company. You need to update the definitions for an existing Logic App. What should you use?
- [ ] the Enterprise Integration Pack (EIP).
- [x] the Logic App Code View.
- [ ] the API Connections.
- [ ] the Logic Apps Designer.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution for a public facing API. The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end. You must configure back-end authentication for the API Management service instance. Solution: You configure Basic gateway credentials for the Azure resource. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution for a public facing API. The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end. You must configure back-end authentication for the API Management service instance. Solution: You configure Client cert gateway credentials for the HTTP(s) endpoint. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution for a public facing API. The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end. You must configure back-end authentication for the API Management service instance. Solution: You configure Basic gateway credentials for the HTTP(s) endpoint. Does the solution meet the goal?
- [ ] Yes.
- [x] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a solution for a public facing API. The API back end is hosted in an Azure App Service instance. You have implemented a RESTful service for the API back end. You must configure back-end authentication for the API Management service instance. Solution: You configure Client cert gateway credentials for the Azure resource. Does the solution meet the goal?
- [x] Yes.
- [ ] No.

**[⬆ Back to Top](#table-of-contents)**

### You are developing a .NET Core MVC application that allows customers to research independent holiday accommodation providers. You want to implement Azure Search to allow the application to search the index by using various criteria to locate documents related to accommodation venues. You want the application to list holiday accommodation venues that fall within a specific price range and are within a specified distance to an airport. What should you do?
- [ ] Configure the SearchMode property of the SearchParameters class.
- [ ] Configure the QueryType property of the SearchParameters class.
- [ ] Configure the Facets property of the SearchParameters class.
- [x] Configure the Filter property of the SearchParameters class.

**[⬆ Back to Top](#table-of-contents)**

### You are a developer at your company. You need to edit the workflows for an existing Logic App. What should you use?
- [ ] the Enterprise Integration Pack (EIP).
- [ ] the Logic App Code View.
- [ ] the API Connections.
- [ ] the Logic Apps Designer.

**[⬆ Back to Top](#table-of-contents)**

### You are developing an application that applies a set of governance policies for internal and external services, as well as for applications. You develop a stateful ASP.NET Core 2.1 web application named PolicyApp and deploy it to an Azure App Service Web App. The PolicyApp reacts to events from Azure Event Grid and performs policy actions based on those events. You have the following requirements: Authentication events must be used to monitor users when they sign in and sign out. All authentication events must be processed by PolicyApp. Sign outs must be processed as fast as possible. What should you do?
- [ ] Create a new Azure Event Grid subscription for all authentication events. Use the subscription to process sign-out events.
- [ ] Create a separate Azure Event Grid handler for sign-in and sign-out events.
- [ ] Create separate Azure Event Grid topics and subscriptions for sign-in and sign-out events.
- [x] Add a subject prefix to sign-out events. Create an Azure Event Grid subscription. Configure the subscription to use the subjectBeginsWith filter.

**[⬆ Back to Top](#table-of-contents)**

### Introductory Info Case study - This is a case study. Case studies are not timed separately. You can use as much exam time as you would like to complete each case. However, there may be additional case studies and sections on this exam. You must manage your time to ensure that you are able to complete all questions included on this exam in the time provided. To answer the questions included in a case study, you will need to reference information that is provided in the case study. Case studies might contain exhibits and other resources that provide more information about the scenario that is described in the case study. Each question is independent of the other questions in this case study. At the end of this case study, a review screen will appear. This screen allows you to review your answers and to make changes before you move to the next section of the exam. After you begin a new section, you cannot return to this section. To start the case study - To display the first question in this case study, click the Next button. Use the buttons in the left pane to explore the content of the case study before you answer the questions. Clicking these buttons displays information such as business requirements, existing environment, and problem statements. When you are ready to answer a question, click the Question button to return to the question. Background - Overview - You are a developer for Contoso, Ltd. The company has a social networking website that is developed as a Single Page Application (SPA). The main web application for the social networking website loads user uploaded content from blob storage. You are developing a solution to monitor uploaded data for inappropriate content. The following process occurs when users upload content by using the SPA: * Messages are sent to ContentUploadService. * Content is processed by ContentAnalysisService. * After processing is complete, the content is posted to the social network or a rejection message is posted in its place. The ContentAnalysisService is deployed with Azure Container Instances from a private Azure Container Registry named contosoimages. The solution will use eight CPU cores. Azure Active Directory - Contoso, Ltd. uses Azure Active Directory (Azure AD) for both internal and guest accounts. Requirements - ContentAnalysisService - The company's data science group built ContentAnalysisService which accepts user generated content as a string and returns a probable value for inappropriate content. Any values over a specific threshold must be reviewed by an employee of Contoso, Ltd. You must create an Azure Function named CheckUserContent to perform the content checks. Costs - You must minimize costs for all Azure services.Manual review - To review content, the user must authenticate to the website portion of the ContentAnalysisService using their Azure AD credentials. The website is built using React and all pages and API endpoints require authentication. In order to review content a user must be part of a ContentReviewer role. All completed reviews must include the reviewer's email address for auditing purposes. High availability - All services must run in multiple regions. The failure of any service in a region must not impact overall application availability. Monitoring - An alert must be raised if the ContentUploadService uses more than 80 percent of available CPU cores. Security - You have the following security requirements: Any web service accessible over the Internet must be protected from cross site scripting attacks. All websites and services must use SSL from a valid root certificate authority. Azure Storage access keys must only be stored in memory and must be available only to the service. All Internal services must only be accessible from internal Virtual Networks (VNets). All parts of the system must support inbound and outbound traffic restrictions. All service calls must be authenticated by using Azure AD. User agreements - When a user submits content, they must agree to a user agreement. The agreement allows employees of Contoso, Ltd. to review content, store cookies on user devices, and track user's IP addresses. Information regarding agreements is used by multiple divisions within Contoso, Ltd. User responses must not be lost and must be available to all parties regardless of individual service uptime. The volume of agreements is expected to be in the millions per hour. Validation testing - When a new version of the ContentAnalysisService is available the previous seven days of content must be processed with the new version to verify that the new version does not significantly deviate from the old version. Issues - Users of the ContentUploadService report that they occasionally see HTTP 502 responses on specific pages. Code - ContentUploadService - You need to add code at line AM09 to ensure that users can review content using ContentAnalysisService. How should you complete the code? To answer, select the appropriate options in the answer area.
- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Introductory Info Case study - This is a case study. Case studies are not timed separately. You can use as much exam time as you would like to complete each case. However, there may be additional case studies and sections on this exam. You must manage your time to ensure that you are able to complete all questions included on this exam in the time provided. To answer the questions included in a case study, you will need to reference information that is provided in the case study. Case studies might contain exhibits and other resources that provide more information about the scenario that is described in the case study. Each question is independent of the other questions in this case study. At the end of this case study, a review screen will appear. This screen allows you to review your answers and to make changes before you move to the next section of the exam. After you begin a new section, you cannot return to this section. To start the case study - To display the first question in this case study, click the Next button. Use the buttons in the left pane to explore the content of the case study before you answer the questions. Clicking these buttons displays information such as business requirements, existing environment, and problem statements. When you are ready to answer a question, click the Question button to return to the question. Background - Overview - You are a developer for Contoso, Ltd. The company has a social networking website that is developed as a Single Page Application (SPA). The main web application for the social networking website loads user uploaded content from blob storage. You are developing a solution to monitor uploaded data for inappropriate content. The following process occurs when users upload content by using the SPA: * Messages are sent to ContentUploadService. * Content is processed by ContentAnalysisService. * After processing is complete, the content is posted to the social network or a rejection message is posted in its place. The ContentAnalysisService is deployed with Azure Container Instances from a private Azure Container Registry named contosoimages. The solution will use eight CPU cores. Azure Active Directory - Contoso, Ltd. uses Azure Active Directory (Azure AD) for both internal and guest accounts. Requirements - ContentAnalysisService - The company's data science group built ContentAnalysisService which accepts user generated content as a string and returns a probable value for inappropriate content. Any values over a specific threshold must be reviewed by an employee of Contoso, Ltd. You must create an Azure Function named CheckUserContent to perform the content checks. Costs - You must minimize costs for all Azure services. Manual review - To review content, the user must authenticate to the website portion of the ContentAnalysisService using their Azure AD credentials. The website is built using React and all pages and API endpoints require authentication. In order to review content a user must be part of a ContentReviewer role. All completed reviews must include the reviewer's email address for auditing purposes. High availability - All services must run in multiple regions. The failure of any service in a region must not impact overall application availability. Monitoring - An alert must be raised if the ContentUploadService uses more than 80 percent of available CPU cores. Security - You have the following security requirements: Any web service accessible over the Internet must be protected from cross site scripting attacks. All websites and services must use SSL from a valid root certificate authority. Azure Storage access keys must only be stored in memory and must be available only to the service. All Internal services must only be accessible from internal Virtual Networks (VNets). All parts of the system must support inbound and outbound traffic restrictions. All service calls must be authenticated by using Azure AD. User agreements - When a user submits content, they must agree to a user agreement. The agreement allows employees of Contoso, Ltd. to review content, store cookies on user devices, and track user's IP addresses. Information regarding agreements is used by multiple divisions within Contoso, Ltd. User responses must not be lost and must be available to all parties regardless of individual service uptime. The volume of agreements is expected to be in the millions per hour. Validation testing - When a new version of the ContentAnalysisService is available the previous seven days of content must be processed with the new version to verify that the new version does not significantly deviate from the old version. Issues - Users of the ContentUploadService report that they occasionally see HTTP 502 responses on specific pages. Code - ContentUploadService - ApplicationManifest - Question You need to ensure that network security policies are met. How should you configure network security? To answer, select the appropriate options in the answer area.

- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**

### Introductory Info Case study - This is a case study. Case studies are not timed separately. You can use as much exam time as you would like to complete each case. However, there may be additional case studies and sections on this exam. You must manage your time to ensure that you are able to complete all questions included on this exam in the time provided. To answer the questions included in a case study, you will need to reference information that is provided in the case study. Case studies might contain exhibits and other resources that provide more information about the scenario that is described in the case study. Each question is independent of the other questions in this case study. At the end of this case study, a review screen will appear. This screen allows you to review your answers and to make changes before you move to the next section of the exam. After you begin a new section, you cannot return to this section. To start the case study - To display the first question in this case study, click the Next button. Use the buttons in the left pane to explore the content of the case study before you answer the questions. Clicking these buttons displays information such as business requirements, existing environment, and problem statements. When you are ready to answer a question, click the Question button to return to the question. Background - Overview - You are a developer for Contoso, Ltd. The company has a social networking website that is developed as a Single Page Application (SPA). The main web application for the social networking website loads user uploaded content from blob storage. You are developing a solution to monitor uploaded data for inappropriate content. The following process occurs when users upload content by using the SPA: * Messages are sent to ContentUploadService. * Content is processed by ContentAnalysisService. * After processing is complete, the content is posted to the social network or a rejection message is posted in its place. The ContentAnalysisService is deployed with Azure Container Instances from a private Azure Container Registry named contosoimages. The solution will use eight CPU cores. Azure Active Directory - Contoso, Ltd. uses Azure Active Directory (Azure AD) for both internal and guest accounts. Requirements - ContentAnalysisService - The company's data science group built ContentAnalysisService which accepts user generated content as a string and returns a probable value for inappropriate content. Any values over a specific threshold must be reviewed by an employee of Contoso, Ltd. You must create an Azure Function named CheckUserContent to perform the content checks. Costs - You must minimize costs for all Azure services. Manual review - To review content, the user must authenticate to the website portion of the ContentAnalysisService using their Azure AD credentials. The website is built using React and all pages and API endpoints require authentication. In order to review content a user must be part of a ContentRev ewer role. All completed reviews must include the reviewer's email address for auditing purposes. High availability - All services must run in multiple regions. The failure of any service in a region must not impact overall application availability. Monitoring - An alert must be raised if the ContentUploadService uses more than 80 percent of available CPU cores. Security - You have the following security requirements: Any web service accessible over the Internet must be protected from cross site scripting attacks. All websites and services must use SSL from a valid root certificate authority. Azure Storage access keys must only be stored in memory and must be available only to the service. All Internal services must only be accessible from internal Virtual Networks (VNets). All parts of the system must support inbound and outbound traffic restrictions. All service calls must be authenticated by using Azure AD. User agreements - When a user submits content, they must agree to a user agreement. The agreement allows employees of Contoso, Ltd. to review content, store cookies on user devices, and track user's IP addresses. Information regarding agreements is used by multiple divisions within Contoso, Ltd. User responses must not be lost and must be available to all parties regardless of individual service uptime. The volume of agreements is expected to be in the millions per hour. Validation testing - When a new version of the ContentAnalysisService is available the previous seven days of content must be processed with the new version to verify that the new version does not significantly deviate from the old version. Issues - Users of the ContentUploadService report that they occasionally see HTTP 502 responses on specific pages. Code - ContentUploadService - ApplicationManifest - Question You need to add code at line AM10 of the application manifest to ensure that the requirement for manually reviewing content can be met. How should you complete the code? To answer, select the appropriate options in the answer area.

- [ ]
- [ ]

**[⬆ Back to Top](#table-of-contents)**
