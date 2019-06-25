# Deploying a little Web-App in Heroku, with Flask - SQlite - JS
> by **Franklin Gonzales**, Georgia US, Jun 2019.
## Specifications
#### Computer Model: **MacBook, pro or air**
#### Operating system: **macOS, Mojave 10.14.5**
## Introduction

Next, I will deploy a Web application, created in Javascript, with queries to the SQLite database from python. In the part of the Back-end, we will have a Flask server. The application, in its entirety, will be transferred to Heroku to deploy on its servers. 
Let us begin!

## Road Map

We have the following 3 big steps:

* Create a virtual environment.
* Create the necessary files to perform deploy.
* Perform the deploy in Heroku.

## Instructions - step by step

#### 1. Create a virtual environment
* From a *terminal*, we created a new directory. For my case, I created the *deploy* directory.
```bash
mkdir deploy
ls -l
```
![](images/001_deployDirectoryCreated.png)

* We must create our own virtual work environment. For this, we will use the *virtualenv* application executed from our new directory. If we do not have the *virtualenv* application, we can install it with:
```bash
pip install virtualenv
```

* Now, we enter our new directory, and execute the command *virtualenv*. When executing the command *virtualenv* we must pass as an argument the name of our virtual environment. For my case, I have chosen the name: *hmwkDeploy*, but we can choose the name we want.
```bash
cd deploy
virtualenv hmwkDeploy
```
![](images/002_hmwkDeploy_Directory.png)

* Basically, when creating our development environment, we created a folder with the same name, which has 3 folders with what is necessary to build a small world of isolated development, within our operating system. Activate our new environment, from our *deploy* folder, with the following command:

## Final specifications.

Whole folder is connected with my GitHub

Path in my local mac:
(/Users/franklingonzales/Documents/GeorgiaTech_DataScienceBOOTCAMP2019/PREWORK_FGC/Module-13 - Interactive Dashboards/FinalHomework/deploy/Heroku-Flask-JS-SQlite-Homework-wk15).

Github Path: [Github WebApp](https://github.com/franklingonzales/Heroku-Flask-JS-SQlite-Homework-wk15.git).
