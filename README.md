# Cloud Computing Lab Program: AWS Web Server Deployment

## Student Details
* **Student Name:** E. Dhanyashree
* **Institution:** Sahyadri College of Engineering & Management, Mangaluru
* **Department:** Computer Science & Engineering (CSE)

## Project Overview
This project was developed as part of the **Cloud Computing Laboratory** coursework. It demonstrates how to provision cloud infrastructure resources and deploy a production-grade departmental web portal on a live cloud environment.

## Architecture & Technology Stack
* **Cloud Platform:** Amazon Web Services (AWS)
* **Virtual Compute Layer:** AWS EC2 Instance Node (Amazon Linux/RHEL)
* **Web Server Software:** Apache HTTP Server (`httpd`)
* **Network Security Configuration:** Custom AWS Security Group configuring Port 80 (HTTP) to accept global web traffic (`0.0.0.0/0`)
* **Frontend Engine:** Semantic HTML5 and custom responsive CSS elements layout

## Lab Execution Deployment Steps
1. Launched a virtual machine environment node inside the AWS EC2 dashboard.
2. Logged into the instance via secure shell terminal command interface.
3. Prepared software packages and dependencies:
   ```bash
   sudo yum update -y
   sudo yum install -y httpd
   ```
4. Initiated and managed the background web service engine:
   ```bash
   sudo systemctl start httpd
   sudo systemctl enable httpd
   ```
5. Authored the frontend layout script mapping the official institutional metrics using the `nano` interface engine.
6. Moved tracking pages into the live server public path hosting directory:
   ```bash
   sudo cp index.html /var/www/html/index.html
   ```
7. Pushed trackable repositories upstream to this GitHub profile account storage directory setup.
