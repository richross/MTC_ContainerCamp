# Container Camp #

# Please check the WIP branch #

The official un-official container camp used to build out containerized applications on Azure.

We assume you have an Azure Subscription... If you don't, break out your Microsoft Account (aka LiveID, Hotmail account, etc) and pick one of these options:

* [Free $200/One Month Trial](https://azure.microsoft.com/en-us/free/) – $200 credit for use in 30 days.
* [Visual Studio Dev Essentials Program](https://www.visualstudio.com/dev-essentials/?campaign=VSBlog_AzureXamAnnoucement_VSDE) – Comes with $25 a month of Azure credit for 12 months.
* [IT Pro Cloud Essentials Program](https://www.microsoft.com/itprocloudessentials/en-US) – Also comes with $25 a month of Azure credit for 12 months.


## Lab One: Create an Azure Linux Jumpbox  ##
In this setup, you will create a linux jumpbox VM in Azure using the Azure Portal, install the Azure cli, and install docker on the vm.

- Setup Step 1: [Deploy a simple Linux VM jumpbox using portal](setup/deploy-linuxjumpbox.md)
- Setup Step 2: [Login to Azure CLI](setup/xplat-cli-login.md)
- Setup Step 3: [Install Docker on the jumpbox](setup/azdockerinstall.md)
- Setup Step 4: [Clone this github respository](setup/gitclone.md)

## Lab Two: Deploy some containers on your jumpbox ##

1. [Use the Jumpbox to deploy containers](labtwo/deploy-docker-vm.md)
2. [Create a custom container](labtwo/buildimage.md)
3. [Instrument & Monitor your containers](labtwo/oms/oms4containers.md)

## Lab Three: Configure a Windows Container Host ##
In this lab you will build a Windows 2016 Server Container Host and deploy Windows containers.

* [Windows Containers on Windows Server](labthree/windows-containers.md)

## Lab Four: Setup Docker Swarm and Deploy Some Containers ##
In this lab you will deploy Docker with swarm mode, using an acs-machine template to deploy to Azure. Once you have a swarm cluster you will deploy some things to it...

* [Deploy a Swarm Mode cluster](labfour/deploy-docker-swarm.md)


## Lab Five: Deploy Multicontainer Applications
* [Deploy multicontainer applications](labfive/multiapp.md)


## Lab Six: Azure Container Instances with ACS and Kubernetes
Deploy containers to Azure in a variety of ways including App Service PaaS and Azure Container Instance vis ACS. Get introduced to Draft and Helm, Cosmos DB, and Application Insights.  Find the complete lab at [Intro to Containers on Azure Lab](https://github.com/shanepeckham/ContainersOnAzure_IntroLab)

