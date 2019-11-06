# cloudformation

## Table of Contents
* [Introduction](#Introduction)
* [How to setup](#How-to-setup)
* [Files](#Files)
* [Features](#Features)

## Introduction
This is scripts to setup a cloud infrastructure that includes network, servers and loadbalancer. 
## How to setup
Please make sure the prerequisit is met before you run the script.
* AWS CLI
* AWS user with programatic access

How to run the script
* Users shoud be given privilege to run two script files
* When create a new stack, we use `create.sh stackname template-name parameter-name`
* When update an existing stack, we use `update.sh stackname template-name parameter-name`
* Please create network before servers

## Files
* yhnetwork.yml
* yhnetworkpara.json
* yhserver.yml
* yhserverpara.json
* create.sh
* update.sh

Two additional files are included, but they are not functional.
* network.yml
* final-project-starter.yml

## Features
* Create a infrastructure using code

### TODO list for this project:

* Students can deploy Windows Servers instead of Linux and use PowerShell scripts to showcase their Windows management skills.
* Students can use AWS Parameter Store to save sensitive data, such as credentials to showcase their attention to security.
* Students can use CloudWatch Alarms and CloudWatch custom metrics to showcase their performance and monitoring skills.
