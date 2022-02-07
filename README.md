# AWS-VPC-EC2Instances-Provisioning-Using-Terraform-Registry-Modules
Using Terraform Registry modules to provision a Virtual Private Cloud and then Provisioning EC2 Instances unto the VPC using Terraform.

The VPC contains the following:
1. 2 subnets, a public and private Subnet
2. Route Tables
3. Internet Gateway
4. Network Access Control List (NACL)
5. The defined CDIR blocks for the public and private subnet

Also, 2 EC2 Instances are provisioned and 2 Elastic IPs which are associated with the EC2 Instances.
