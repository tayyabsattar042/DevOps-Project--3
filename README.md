# DevOps-Project--3: Deploying a Node.js Application on AWS EC2

This guide outlines the deployment of a Node.js application onto an AWS EC2 instance, ensuring a professional and scalable approach.

## Local Project Testing
- Clone the repository to your local machine.
- Configure necessary environment variables within a `.env` file.
- Initialize and start the application to verify functionality.

## AWS EC2 Instance Setup
- Establish an IAM user and sign in to the AWS Management Console.
- Launch an EC2 instance selecting Ubuntu as the operating system.
- Generate a new key pair, download the `.pem` file, and note the instance type as 't2.micro'.
- Connect to the instance via SSH.

## Configuring the Ubuntu Server
- Perform updates to packages and dependencies.
- Follow DigitalOcean's guide to install Git.
- Set up Node.js and npm as per DigitalOcean's instructions.

## Application Deployment on AWS
- Clone the application repository onto the remote virtual machine.
- Set up the required environment variables within a `.env` file on the VM.
- Start the application, confirming successful deployment.

The application is deployed on AWS EC2, marking a milestone in efficient and scalable web application deployment.
