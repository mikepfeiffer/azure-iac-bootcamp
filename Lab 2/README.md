# Lab 2: Configure Your IaC Developer Tools

1. Start up a new Azure Lab instance on my.ine.com.
2. Open the Azure portal (you'll notice you have one resource group available).
3. Create a new storage account inside your resource group.
4. Start the Azure Cloud Shell (use bash or powershell, your choice).
5. Configure the advanced settings of the cloud shell. You'll need to persist your files in a new share within your new storage account.
6. Launch VS Code and install the Azure Account extension.
7. Open a terminal in VS Code and select "Azure Cloud Shell (Bash)"
8. Sign into Azure using your temporary Azure AD user account provided by your INE Lab instance.
9. Locate the clone url for the repo you created in [Lab 1](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%201)
10. Use the Cloud Shell in VS Code to clone your GitHub repo into your cloud shell instance.
11. Navigate the file system in the cloud shell to confirm that your clone operation succeeded. 

## Challenge

After you've completed this lab, practice your Git workflow skills again. Make sure your local repos are up-to-date, and then make a change to your README. Commit and push your changes to GitHub, and pull the updates into the copy you have inside your Cloud Shell.


## Lifelines

Create a storage account
* https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create

Persist files in Azure Cloud Shell
* https://docs.microsoft.com/en-us/azure/cloud-shell/persisting-shell-storage

Azure Account extension
* https://marketplace.visualstudio.com/items?itemName=ms-vscode.azure-account

Setting up a repository: git clone
* https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone

## Next Lab
**[Lab 3: Create Your First ARM Template](https://github.com/mikepfeiffer/azure-iac-bootcamp/tree/main/Lab%203)**

## Lab Index
[github.com/mikepfeiffer/azure-iac-bootcamp](https://github.com/mikepfeiffer/azure-iac-bootcamp)