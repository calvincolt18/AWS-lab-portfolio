# AWS-lab-portfolio
Hands-on AWS projects:EC2,S3,IAM, and more using Loom and Github.


GitHub README Structure for EC2 Project
# AWS EC2 Instance Deployment Lab

## Overview
This lab demonstrates how to launch and connect to a virtual server (EC2 instance) using AWS. EC2 allows users to create scalable cloud servers.

## Steps Performed
1. Logged into AWS Console and navigated to EC2
2. Launched a new EC2 instance using Amazon Linux 2
3. Selected `t2.micro` as instance type (free-tier eligible)
4. Configured key pair for SSH access
5. Set security group to allow SSH from my IP
6. Launched the instance and verified it was running
7. Connected to the instance using SSH via terminal

## Tools Used
- AWS Management Console
- EC2
- SSH
- GitHub
- Loom

## Project Video
[Loom EC2 Walkthrough Video] https://www.loom.com/share/e4d430c1975f4347a1bb0d42e63ab382  https://www.loom.com/share/26396c8e2e4044f8a8d3920fe42772fa

## Author
Calvin Alexander


# AWS S3 Bucket and Object Upload Lab

## Overview
This lab demonstrates how to create an AWS S3 bucket and upload an object (file) into that bucket, simulating real-world cloud storage practices.

## Tools Used
- AWS Management Console
- AWS S3
- Loom (for video recording)

## Steps Performed
1. Logged into AWS Console.
2. Navigated to S3 service.
3. Clicked “Create bucket”.
4. Entered a unique bucket name (e.g., `calvin-s3-demo-bucket`).
5. Left default settings and disabled public access.
6. Created the bucket successfully.
7. Opened the bucket and uploaded a sample `.txt` file.
8. Verified the file was stored and listed within the bucket.

## Key Concepts
- Object Storage
- Bucket Permissions
- S3 Access Management
- Cloud Data Storage Fundamentals

## Loom Video Walkthrough
📹 [Click here to view the S3 Bucket Lab on Loom] https://www.loom.com/share/2304b19422e2456fbd0f1c3186074c23



# AWS IAM User Creation and Permission Assignment

## Objective
To create a new IAM user with programmatic access and assign a basic permission policy.

## Tools Used
- AWS Management Console

## Steps
1. Navigated to the IAM service from the AWS Console
2. Created a new IAM user named `labuser1`
3. Enabled programmatic access
4. Attached the `AmazonS3ReadOnlyAccess` policy
5. Viewed and verified user permissions after creation

## Skills Practiced
- Identity management
- Policy attachment
- Access key management

## Outcome
User created successfully with limited access policy applied.

## Video Demonstration
[Loom Video Link] https://www.loom.com/share/87ac1118301c4c9b9f6209228ccddb07





# AWS VPC and Subnet Configuration

## Objective
To create a custom Virtual Private Cloud (VPC) and define a subnet within that VPC.

## Tools Used
- AWS Management Console

## Steps
1. Created a VPC named `custom-vpc`
2. Defined a subnet named `custom-subnet` in an availability zone
3. Used CIDR block `10.0.1.0/24` for subnet
4. Verified networking layout in the dashboard

## Skills Practiced
- Network segmentation
- Subnet configuration
- Custom VPC design

## Outcome
Successfully created isolated VPC and configured subnet.

## Video Demonstration
[Loom Video Link] https://www.loom.com/share/ec17cf2e41984bdb86f362f2c778b942

