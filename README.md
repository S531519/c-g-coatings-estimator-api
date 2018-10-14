# Adonis fullstack application

This is the fullstack boilerplate for AdonisJs, it comes pre-configured with.

1. Bodyparser
2. Session
3. Authentication
4. Web security middleware
5. CORS
6. Edge template engine
7. Lucid ORM
8. Migrations and seeds

## System Requirements
The only dependencies of the framework are Node.js and npm. Ensure that the version of those tools meets the following.

Node.js >= 8.0.0

npm >= 3.0.0

## Adonis Installation 
Go to AdonisJS home page (https://adonisjs.com/docs/4.1/installation) to install from Git repository or to install from command promt follow given instructions

Adonis CLI is a command line tool to help you install AdonisJs.
```bash
 npm i -g @adonisjs/cli 
```
Once done, you can make use of adonis new command that will create a fresh installation of AdonisJs.

```bash
     adonis new yardstick
```

Now go to the new yardstick directory by using cd command
```bash
 cd yardstick
 ```
Once the installation process is completed, you can cd into the directory and run the following command to start the HTTP Server.

```bash
 adonis serve --dev
```
This command starts the server on the port defined inside the .env file. Use the server to check weather installation is succesfull.

## Setup

Use the adonis command to install the blueprint

```bash
adonis new yardstick
```

or manually clone the repo and then run `npm install`.


### Migrations

Run the following command to run startup migrations.

```js
adonis migration:run
```
