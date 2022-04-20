# Lab 5: Create and Deploy a Bicep Template


1. Create a new repo, follow the same steps in [Lab 1](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%201) but this time name your repo "iac-bicep-project"
2. Once you've got a local copy of "iac-bicep-project", open it in VS Code.
3. Install the [Bicep](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep) VS Code extension.
4. Create a new file called **main.bicep**
5. Add an Azure Storage Acccount and a Virtual Network resource to your **main.bicep** file.<br>(hint: there's already a completed version in the [/templates](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%205/templates) folder of this repo).
6. Add, commit, and push your changes to GitHub.
7. Start up a new Azure Lab instance on my.ine.com
8. Open the cloud shell (the steps on how to do this are covered in [Lab 2](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%202)).
9. Find the GitHub clone URL for your "iac-bicep-project" repo.
10. Clone the repo into your cloud shell.
11. Use the Azure CLI to deploy the Bicep template.
12. View the deployment history to confirm confirm everything worked.
7. Click "stop" to terminate your INE Lab instance.


## Challenge

Now that you've done a Bicep deployment, re-start the lab and try adding a template spec (check the lifelines below).


## Lifelines

Create Bicep files with Visual Studio Code
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/quickstart-create-bicep-use-visual-studio-code

Create and deploy a template spec with Bicep
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/bicep/quickstart-create-template-specs

Bicep VS Code extension
* https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-bicep

## Next Lab
**[Lab 6: Perform an Automated ARM Template Deployment using GitHub Actions](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%206)**

## Lab Index
[github.com/mikepfeiffer/azure-iac-bootcamp](https://github.com/mikepfeiffer/azure-iac-bootcamp)