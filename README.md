# Arc-enabledWinServersDemoLab
In this small demo environment I would like to show how easy it is to integrate a Virtual Machine into Azure Arc.

There are countless Github repositories that can be used to build a demo environment in Azure. I chose a repository that allows me to have multiple options at the same time. This repository deployed with Azure Bicep various Hub and Spoke networks. Therefore, I also saved myself the time and did not create a separate repository for it.

Put the right things together! ;-)


## Step 1 - Deploy Demo Lab via Bicep Github Repo
With Step 1, we will create the basic environment in Azure. 

For this we need:
- a hub network with Bastion Host, VNet, VPN Gateway
- a "simulated" on-prem spoke network with VNet, gateway and S2S VPN to Hub.

A virtual machine will later be deployed into the on-prem spoke network (see step 2).


### Deploy to Azure

| Description | Template |
|---|---|
| Deploy to Azure Subscription |[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#blade/Microsoft_Azure_CreateUIDef/CustomDeploymentBlade/uri/https%3A%2F%2Fraw.githubusercontent.com%2FPieterbasNagengast%2FAzure-HubSpoke-LabBuilder%2Fmain%2FARM%2Fmain.json/uiFormDefinitionUri/https%3A%2F%2Fraw.githubusercontent.com%2FPieterbasNagengast%2FAzure-HubSpoke-LabBuilder%2Fmain%2FuiDefinition.json)|

> :warning: **Warning:**
> **This deployment is meant for Demo, Test, Learning, Training, Practice or Reproduction purposes ONLY!!**
> **Please don't deploy to production environments!!**







## Step 2 - Deploy Azure Virtual Machine in "On-Prem" Resource Group






## Step 3 - Azure Portal - Arc Overview
