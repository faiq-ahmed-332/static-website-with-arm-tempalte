Overview:

This read-me defines the steps taken in order to deploy a static website on azure storage account through ARM tempalte and Azure DevOps Pipeline:

* Setting up Azure ResourceGroup thourgh ARM Template (in Progress)
* Setting up Azure Storage Account with Static Website hosting.
* Configuring Azure CDN through the ARM template to serve the Static Website hosting.
* Setting Up Blue Green Deployment using Azure App Service Deployment slots (Todo)


Files and their Purpose:

* deploy.yaml: create storageAccount, CDN and deploy the static site on the storage account.
* deploy.parameters.yaml: Parameters file for the ARM Template.
* index.html: landing page for the static website.
* azure-pipeline.yaml: Azure DevOps pipeline configuration.
* rg-deploy.yaml: ARM Template to create a resource group
* rg-deploy.parameters.yaml: Parameters file for the resource group ARM Template.


Steps to Setup:

* Setup resource group
* Setup storage account and CDN
* Configure Azure DevOps Pipeline
* Run the pipeline

