# Lab 1 - Create an Infrastructure as Code (IaC) Repo in GitHub

1. Launch the load balancer ARM template from [here](https://github.com/AzureInterface/quickstart/tree/master/azure-load-balancer) Note: The VM types in the template may not be available in your Azure Pass. You can edit the template during launch to use the Standard_B2s VM size.
2. Verify you can connect remotely via NAT rules
3. Set up a basic web server / web page on each VM
4. Create a HTTP probe for the load balancer
5. Create a load balancer rule for HTTP
6. Verify you can visit your website through the load balancer
7. Verify your load balanced site still works after killing one of the web servers
8. Delete the resource group from your Azure Pass subscription when complete

### Notes

Azure Load Balancer overview
* https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-overview

Creating an Internet-facing load balancer using the Azure portal
* https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-get-started-internet-portal

Install IIS
* https://docs.microsoft.com/en-us/windows-server/networking/core-network-guide/cncg/server-certs/install-the-web-server-web1
