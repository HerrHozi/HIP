# Read Me
How to write a good README for your GitHub project?


## Table of contents
* [General Info](#general-info)
* [Herr Hozi Blog](#my-blog)
* [Technologies](#technologies)
* [Setup](#setup)
* [Installation](#installation)

## General info
This project is simple Lorem ipsum dolor generator.
	
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999

## Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Next.js](https://nextjs.org/)
* [React.js](https://reactjs.org/)
* [Vue.js](https://vuejs.org/)
* [Angular](https://angular.io/)
* [Svelte](https://svelte.dev/)
* [Laravel](https://laravel.com)
* [Bootstrap](https://getbootstrap.com)
* [JQuery](https://jquery.com)

	
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


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```![image](https://user-images.githubusercontent.com/96825160/147820129-cc3c5bdb-21a3-4cd4-a32c-8b222a1eac5c.png)


## My Blog

Check out  [https://herrhozi.com](https://herrhozi.com)

