# Lab 4: Deploy an ARM Template Interactively

1. Start up a new Azure Lab instance on my.ine.com (if you don't have one already).
2. Open the cloud shell (the steps on how to do this are covered in [Lab 2](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%202)).
3. Find the clone URL for the repo you setup in [Lab 3](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%203).
4. Clone the repo into your cloud shell.
5. Perform a "local" ARM template deployment from the cloud shell using Azure CLI.
6. View the deployment history to confirm everything worked.
7. Click "stop" to terminate your INE Lab instance.

## Challenge

Stop your Azure Lab instance on my.ine.com and start a new one. Follow the steps in this lab again, but use PowerShell on step 5 instead of the Azure CLI.

## Bonus Points

Secondary deployments for existing resource groups are common when you need to update resources. How could you do a second deployment to update the storage account created by the first deployment?

## Lifelines

Deploy a local ARM template
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-tutorial-local-template

Create and Deploy your first ARM template
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template

View deployment history with Azure Resource Manager
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/deployment-history

Update a resource in an Azure Resource Manager template
* https://docs.microsoft.com/en-us/azure/architecture/guide/azure-resource-manager/advanced-templates/update-resource

## Next Lab
**[Lab 5: Create and Deploy a Bicep Template](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%205)**

## Lab Index
[github.com/mikepfeiffer/azure-iac-bootcamp](https://github.com/mikepfeiffer/azure-iac-bootcamp)