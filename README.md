# ICT171 Cloud Server Project - Cybersecurity Awareness Website

## Student Details

## Name: Yasmin Adam Mohammed 

Student Number: 33514069

## Project Title

Cloud server project - Cybersecurity Awareness Website 

## Live Website

Website URL: 
http://cybersecurityawarenessserver.australiaeast.cloudapp.azure.com

## Project Overview

This project involves the development of a cloud hosted cybersecurity awareness website using Infrastructure as a Service (IaaS).
The website aims to educate users about common cybersecurity threats, password security, phishing attacks, multi-factor authentication and online safety practices.
The project will be deployed on a Linux cloud server hosted in Microsoft Azure and will include:
- Apache Web Server
- DNS Configuration
- SSL/TLS Encryption
- GitHub Documentation
- Bash Scripting
- Cloud Hosting
  
## Project Status
  
Status: Completed 

Completed Components:
- Microsoft Azure Virtual Machine deployment
- Ubuntu Linux server confirguration
- Apache2 web server installation
- Azure DNS hostname setup
- SSH remote management
- Cybersecurity Awareness website.
- Custom Bash monitoring script.
- GitHub documentation.

## Technologies Used

- Microsoft Azure
- Ubuntu Linux
- Apache2
- SSH
- HTML
- CSS
- Bash scripting
- GitHub

## Server Build Guide

## Step 1 - Create Azure Virtual Machine

1. Log into Microsoft Azure portal.
2. Create a new virtual machine.
3. Select Ubuntu Linux.
4. Configure SSH access
5. Allow inbound ports SSH 22 and HTTP 80.

## Step 2 - Connest using SSH

ssh -i cyberawarenessserver_key.pem azureuser@SERVER-IP

SSH was used to securely connect to the  Azure virtual machine and manage the server remotely.

## Step 3 - Install Apache

sudo apt update
sudo apt install apache2 -y

Enable and start Apache2:

sudo systemct1 enable apache2
sudo systemct1 start apache2
sudo systemct1 status apache2

## Step 5 - Deploy Website Files

Navigate to the Apache web directory:

cd /var/www/html

Edit the website:

sudo nano index.html

Website files and images were uploaded into the Apache web directory and tested through a web browser.

## Step 6 - Configure Azure DNS Hostname

An Azure DNS hostname was configured so the website could be accessed using a user-friendly URL instead of only a public IP address. 

http://cybersecurityawarenessserver.australiaeast.cloudapp.azure.com

## Step 7 - Create Custom Bash Script

nano serverinfo.sh
chmod +x serverinfo.sh
./serverinfo.sh

The script displays:

- Hostname
- Date and time
- System uptime
- Disk usage
- Memory usage

## Script Explanation

The serverinfo.sh script provides a quick overview of the server status. It displays useful information such as hostname, date and time, uptime, disk usage and memory usage. This assists with basic server monitoring and troubleshooting.
  
## GitHub Development Log
  
### 31 May 2026 
- Repository created on GitHub.
- Project structure planned and documented.
- Initial README file created.

### 1 June 2026
- Microsoft Azure subscription reactivated
- SSH access restored
- Ubuntu Linux server configured.
- Apache2 web server installed and tested.
- Azure DNS hostname configured and verified.
- Website successfully confirmed through DNS hostname.

### 2 June 2026
- Developed initial cybersecuirty awareness website.
- Added website sections covering cybersecurity risks and online safety tips.
- Created custom Bash monitoring script (serverinfo.sh).
- Tested script functionality on Ubuntu server.
- Uploaded website files to Apache web root directory.

### 3 June 2026
- Improved website structure and navigation menu.
- Added layout and modern styline using CSS.
- Updated GitHub repository documentation.
- Organised project files into Documentation, Scripts and Website folders

### 4 June 2026
- Added cybersecurity awareness content.
- Refined website colour scheme and visual design.
- Improved section layout and user experience.
- Verified server connectivity and website functionality.
- Reviewed project with assessment requirements.

### 5 June 2026
- Added professional cloud infrastructure hero image.
- Redesigned website hosting details section.
- Enhanced website branding and visual presentation.
- Updated project overview.
- Performed final testing of website navigation and content.
- Verified Azure DNS hostname accessibilty.
- Updatd GitHub repository with lastest project changes.
- Completed final website refinements and project documentation. 

## Screenshots

The repository includes screenshots of demonstarting:

- Azure Virtual Machine running
- SSH connection to the server
- Apache2 service active and running
- Website homepage
- Website hosting details section
- serverinfo.sh script output
- Github repository structure

## References 
