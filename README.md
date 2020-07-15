# Azure Kubernetes and dependencies Deployment Template

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-storage-account-create%2Fazuredeploy.json" target="_blank">
  <img src="https://aka.ms/deploytoazurebutton"/>
</a>


This sample template creates following Azure components and its dependencies.

1. Azure AKS Instance.
2. Virtual network, Subnet, Network Security Group.
3. Event Hub
4. Log Analytics workspace
5. Redis Cache
 
 Create a resource group with below command

PS> New-AzureRmResourceGroup -Name perf-Tan-SI-RG-AKS-01 -Location "South Central US"

The purpose of this template is to deploy AKS cluster with all of dependent resources.
