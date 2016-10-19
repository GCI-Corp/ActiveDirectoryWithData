# ActiveDirectoryWithData
Script that creates and populates Active Directory
PowerShell Server 2012R2 w/ ActiveDirectory

#First, we need to load the modules necessary to run the script. 

#We will load the Azure Resource Manager modules. Note: there are 28, this step takes a minute
Install-Module AzureRM -Force -Verbose 

#This will install the Azure Service Management module
Install-Module Azure -Force -Verbose

#This command installs xActiveDirectory tools which are used automate the setup of ActiveDirectory
Install-Module xActiveDirectory -Force -Verbose

#Log in to Azure via PowerShell ISE CLI
Login-AzureRMAccount

#Defines Variables for the script we will run in the next step
$URI                =  ‘
$Location       =
$rgname         =
$saname         =
$addnsName  = 
