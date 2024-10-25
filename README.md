# AWS CloudFormation Resource Provisioning

This project demonstrates how to use AWS CloudFormation to provision and manage AWS infrastructure resources. Through this project, we will explore creating a VPC, subnets, EC2 instances, security groups, S3 buckets, IAM roles, and VPC endpoints to enable secure and efficient cloud architecture.

## Project Overview

AWS CloudFormation is a powerful tool for managing AWS resources as code. This project explores various CloudFormation features and techniques, such as creating reusable templates, managing resources in both public and private subnets, and securely accessing services using VPC endpoints and IAM roles.

## Features

- **VPC and Networking**: Creates a Virtual Private Cloud (VPC) with public and private subnets, route tables, and internet gateways.
- **EC2 Instances**: Provisions EC2 instances in a private subnet and enables access via AWS Systems Manager (SSM) instead of SSH.
- **S3 Bucket with VPC Endpoint**: Configures an S3 bucket and restricts access to it via a VPC endpoint from instances in the private subnet.
- **IAM Roles and Policies**: Configures IAM roles for EC2 instances to allow SSM and S3 access.
- **VPC Endpoints**: Sets up endpoints for secure communication between resources within the VPC and other AWS services.

## Prerequisites

- **AWS Account**: You must have an active AWS account.
- **AWS CLI**: The AWS CLI should be installed and configured with necessary permissions.
- **IAM User with Permissions**: Ensure you have an IAM user with permissions to create CloudFormation stacks, EC2 instances, S3 buckets, IAM roles, and VPC resources.

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/aws-cloudformation-provisioning.git
cd aws-cloudformation-provisioning
