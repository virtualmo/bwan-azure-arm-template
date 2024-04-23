# 1. Borderless SD-WAN Gateway Deployment on Azure

## 1.1. Introduction

This template will deploy a Netskope Borderless SD-WAN Gateway Deployment on Microsoft Azure

The template assumes the following a Requirement:

- Existing and Active Microsoft Azure Subscription
- If you don't have a Azure Subscription visit please <https://azure.microsoft.com/en-us/free/> and create one
- Netskope Borderless WAN tenant


## 1.2. Deploy Azure Environment

Click on the Deploy button to deploy single Netskope Borderless SD-WAN Gateway with two interfaces (1xPublic and 1xPrivate). The template doesn’t include the applications vNet deployment nor the branch offices.

<p align="center">
<img src="https://github.com/virtualmo/bwan-azure-arm-template/blob/main/images/Topology.png">
</br>
</p>

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fvirtualmo%2Fbwan-azure-arm-template%2Fmain%2FazureDeploy.json)

## 1.3. Gateway activation

The gateway will need to be activated after the deployment.
