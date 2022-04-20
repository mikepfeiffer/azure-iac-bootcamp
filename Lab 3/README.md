# Lab 3: Create Your First ARM Template

1. Open VS Code on your computer.
2. Install the [Azure Resource Manager (ARM) Tools](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools) extension.
3. Open the repo your created in [Lab 1](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%201) in VS Code.
4. Create a new file called **azuredeploy.json**
5. Add an Azure Storage Acccount resource to your **azuredeploy.json** template.<br>(hint: there's already a completed version in the /templates folder).
6. Add, commit, and push your changes to GitHub.


## Challenge

Stop your Azure Lab instance on my.ine.com, and then start a new one. Create a storage account inside your resource group and export the resource group to an ARM template. Compare this template to the one you created manually and see if you can find any differences.

## Bonus Points

Take a look at your **azuredeploy.json** template. Think creatively how you could make use of template parameters, functions, and variables to customize this template. 

## Lifelines

Azure Resource Manager (ARM) Tools
* https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools

Create your first ARM template
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/templates/template-tutorial-create-first-template

Use exported template from the Azure portal
* https://docs.microsoft.com/en-us/azure/developer/javascript/how-to/with-visual-studio-code/clone-github-repository

## Next Lab
**[Lab 4: Deploy an ARM Template Interactively](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%204)**