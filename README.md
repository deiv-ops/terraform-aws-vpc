---
title: Terraform Remote State Storage with AWS S3 & DynamoDB
description: Store Terraform State in AWS S3 and Implement State Locking with AWS DynamoDB
---
# Terraform Remote State Storage and State Locking with AWS S3 and DynamoDB

Introduction
- Understand Terraform Backends
- Understand about Remote State Storage and its advantages
- This state is stored by default in a local file named "terraform.tfstate", but it can also be stored remotely, which works better in a team environment.
- Create AWS S3 bucket to store `terraform.tfstate` file and enable backend configurations in terraform settings block
- Understand about **State Locking** and its advantages
- Create DynamoDB Table and  implement State Locking by enabling the same in Terraform backend configuration

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-1.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-1.png)

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-2.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-2.png)

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-3.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-3.png)

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-4.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-4.png)

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-5.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-5.png)

[![Image](https://stacksimplify.com/course-images/terraform-remote-state-storage-6.png "Terraform on AWS with IAC DevOps and SRE")](https://stacksimplify.com/course-images/terraform-remote-state-storage-6.png)
