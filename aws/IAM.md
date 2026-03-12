
<strong>AWS IAM (Identity and Access Management)</strong>

What is IAM

AWS IAM (Identity and Access Management) is a service that helps you securely control access to AWS resources. It allows you to manage users, permissions, and roles in your AWS account.

Using IAM, administrators can decide who can access AWS resources and what actions they can perform.


<strong>Key Components of IAM</strong>

1. IAM Users

An IAM user represents a person or application that uses AWS services.

Example:

1.Developer

2.Administrator

3.Application service

Each user can have:-

1.Username

2.Password for AWS Console

3.Access keys for CLI or API


2. IAM Groups

An IAM group is a collection of IAM users. (assining user into a group )

It helps manage permissions easily. If you assign permission to the group, all users inside the group get the same permission.


4. IAM Policies

Policies are JSON documents that define permissions.

They specify:

What actions are allowed

Which resources can be accessed

Example policy:-

{
 "Version": "2012-10-17",
 "Statement": [
  {
   "Effect": "Allow",
   "Action": "s3:ListBucket",
   "Resource": "*"
  }
 ]
}