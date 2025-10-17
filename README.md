# HNG13 Stage 0 - Devops

- **Name**: Abdulbaki Suraj
- **Slack username**: InfraNomad
- **Server IP**: [44.223.4.107](http://44.223.4.107/)

## Project Description

### Overview

This project is a hands-on Devops challeng designed to simulate real-world deployment workflows.
The goal is to
- set up and manage a Github repository for version control & automation
- provision a live server on AWS
- install and configure NGINX as a web server
- serve a custom web page accessible via a pubic IP
- configure a CI/CD pipeline with Github Actions to automate deployment

### Tech Stack
- AWS - Cloud service provider
- NGINX - web server
- Github Actions - CI/CD automation
- Linux (Ubuntu) - deployment environment
- Git & SSH - version control and secure access
- HTML - static web content

## Setup
- on AWS, setup an EC2 instance with an Ubuntu AMI
- copy the ssh key used during setup as well as public ipv4 address generated after the instace was created
- add these values to the Github repo secrets (Settings -> Secrets and variables -> Actions -> New repository secrets)
- manually run the Github Action to test it (this also run automatically for every push to the repo)