# 🌐 AWS EC2 Web Server Deployment with Custom AMI

This repository documents the deployment of a Windows-based EC2 web server on AWS, showcasing how to create a reusable Amazon Machine Image (AMI) for backup and recovery of a web application.

## 📌 Project Summary

 **Platform**: Amazon Web Services (AWS)
 **Service Used**: EC2, AMI, EBS
 **Instance Type**: `t3.micro`
 **Operating System**: Windows Server
 **Region**: `us-east-1a`

## 🔄 Workflow Overview

1. **Launch EC2 Instance**  
    Deployed a Windows-based EC2 instance configured as a web server.

2. **Create AMI from Running Instance**  
    Generated a custom AMI to preserve the web server configuration and application state.

3. **Terminate Original Instance**  
    Safely terminated the initial EC2 instance after AMI creation.

4. **Launch New EC2 from AMI**  
    Deployed a new EC2 instance using the custom AMI.  
    The web application was successfully restored, confirming the AMI preserved all necessary configurations and data.

## ✅ Key Outcomes

 🔁 Achieved seamless backup and recovery of a web application using AMI  
 🧩 Validated AMI-based deployment for consistent infrastructure replication  
 🔐 Ensured secure and scalable setup using AWS best practices

## 📚 Learning Highlights

 How to create and manage AMIs for Windows EC2 instances  
 How AMIs preserve application state and configuration  
 How to restore terminated instances using custom AMIs

## 🏷️ Tags

`AWS` `EC2` `Windows Server` `AMI` `Cloud Backup` `Web Server` `Infrastructure as Code`

---

Would you like a matching LinkedIn post to showcase this workflow or a diagram to visualize the process?
