# Read Me
How to write a good README for your GitHub project?


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Get-DomainUserList Module](#Get-DomainUserList-Module)

## General info
This project is simple Lorem ipsum dolor generator.
	
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
	
## Setup
To run this project, install it locally using npm:
```
$ cd ../lorem
$ npm install
$ npm start
```

## Get-DomainUserList Module
The function Get-DomainUserList allows you to generate a userlist from the domain. It has options to remove disabled accounts and those that are about to be locked out. This is performed automatically in DomainPasswordSpray if no user list is specified. 

This command will write the domain user list without disabled accounts or accounts about to be locked out to a file at "userlist.txt".
```PowerShell
Get-DomainUserList -Domain domainname -RemoveDisabled -RemovePotentialLockouts | Out-File -Encoding ascii userlist.txt
```
