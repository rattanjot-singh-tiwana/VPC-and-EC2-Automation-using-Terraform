# 🏗️ VPC-and-EC2-Automation-using-Terraform

## 📜 Project Overview

Deployment of a highly available web application infrastructure on AWS using Terraform. Key components include a VPC, subnets, security groups, EC2 instance for the application, and an RDS instance for persistent storage.


## 🛠️ Infrastructure Components
* VPC - 10.0.0.0/16 network with DNS support.
* Subnets - Spread across different AZs for fault tolerance.
* Security Groups - Allowing only necessary HTTP AND DATABASE access.
* EC2 Instance - Deployed in a private subnet with public access only as required.
* RDS Instance - MySQL database setup with backup and patch management by AWS.


## Prerequisties
* Terraform installed
* AWS CLI configured with appropriate IAM permissions


## DEPLOYMENT STEPS 

    Step 1: Initialize the Terraform workspace
    terraform init
    
    Step 2: Preview the infrastructure changes
    terraform plan
    
    Step 3: Deploy the resources
    terraform apply


## 📝 Notes
* Ensure that AWS credentials are correctly configured
* Update the secure database password in rds instance 



