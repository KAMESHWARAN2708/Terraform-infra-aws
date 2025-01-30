# AWS VPC Setup

This repository contains resources for creating a Virtual Private Cloud (VPC) in AWS. It includes the following components:

- **IAM (Identity and Access Management)**: Initial setup for managing permissions and roles.
- **IGW (Internet Gateway)**: Setup for allowing traffic to and from the internet.
- **LB (Load Balancer)**: Setup for distributing incoming traffic across multiple instances.
- **NAT (Network Address Translation)**: Setup for allowing private subnet instances to access the internet.
- **Provisioner**: Resources for automating the deployment process.
- **RT (Route Table)**: Configuration for managing routes in your VPC.
- **S3 (Simple Storage Service)**: Setup for S3 buckets within the VPC.
- **SG (Security Groups)**: Configuration for controlling inbound and outbound traffic.
- **Subnet**: Subnet configurations to divide the VPC into segments.
- **VPC (Virtual Private Cloud)**: Core setup for creating the VPC itself.

## Requirements

- AWS CLI configured with the necessary credentials and region.
- Terraform installed on your machine.
- Access to the AWS account with the necessary permissions for VPC, EC2, IAM, etc.

## Usage

### 1. Clone the Repository

```bash
git clone <repository_url>
cd <repository_directory>
