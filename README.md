# Electronics_Schematics
This repository contains diagrams of Wanderer's electrical systems as well as PCBs designed by the Electronics sub-team.

# Table of Contents
[Downloading the Repository](#downloading-the-repository)   
[Required Software](#required-software)  
[Repository Contents](#repository-contents)  

# Downloading the Repository
## Pre-Install: SSH Key
An ssh key for your current machine must be added to your Github account to clone our repositories.  
SSH keys are used for passwordless authentication.  
For more information see https://docs.github.com/en/authentication/connecting-to-github-with-ssh.

## Creating an SSh Key
`$ ssh-keygen`  
Keep the default file name, add a password if you'd like. 

## Adding the SSH Key to your Github account
Go to https://github.com/settings/keys and click "New SSH Key"  
The title can be anything.  
For Key, copy paste the output of `$ cat ~/.ssh/id_rsa.pub`

## Clone the workspace
Install git if not done so already with `$ sudo apt install git` then:  
`git clone git@github.com:wvu-urc/electronics_schematics.git ~electronics_schematics`
* If this is your first time talking to Github on your machine, you will receive a warning saying authenticity cannot be established.  
	Type "yes" and hit enter.

# Required Software
Block diagrams and schematics can be viewed using any PDF viewer.
All PCBs were designed using KiCad 7.0. The most recent version of the software can be downloaded at https://www.kicad.org/download/.

# Repository Contents

## System Schematics

Main Electronics Box Diagram

Manipulator Electronics Diagram

Science Electronics Diagram

## PCB Files

Battery Monitor v1.2

Payload PCB v3.1

Power Distribution Board