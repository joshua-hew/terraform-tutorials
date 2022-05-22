# Learning Terraform

This repo contains terraform config files used to follow along with the official [Terraform tutorials](https://learn.hashicorp.com/terraform)

<strong> Learning Goals </strong>
My goals for learning Terraform is three-fold:
- Learn the basic concepts
- Go through the AWS tutorial
- Deploy a basic todo app on AWS using Terraform

Bonus:
- Deploy the same todo app on Azure and Google Cloud

<strong> Lessons learned </strong>
- Migrating from local to Terraform cloud can cause difficulties in a multi-account env
- Using 'assumeRole' is a more reliable way of deploying across accounts compared to using 'profile' and exporting the "AWS_PROFILE" env variable. Worked locally, but not when using Terraform cloud.