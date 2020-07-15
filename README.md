# Azure Kubernetes and dependencies Deployment Template

[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)

This sample template creates following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hub
4. Log Analytics workspace
5. Redis Cache
 
 Create a resource group with below command

PS> New-AzureRmResourceGroup -Name perf-Tan-SI-RG-AKS-01 -Location "South Central US"

The purpose of this template is to deploy AKS cluster with all of dependent resources.
