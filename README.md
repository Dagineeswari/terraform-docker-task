# terraform-docker-task
# Infrastructure as Code (IaC) with Terraform

## Overview
This project provisions a local Nginx Docker container using Terraform as part of Task 3 of the DevOps Internship.

## Files Included
- `main.tf`: Terraform configuration file defining the Docker provider, Nginx image, and container resource.
- Screenshots / Logs: Execution proof for `terraform init`, `plan`, `apply`, `state`, and `destroy`.

## Steps Executed
1. `terraform init` - Downloaded required Docker provider plugins.
2. `terraform plan` - Verified planned resource changes.
3. `terraform apply` - Created and started the Nginx Docker container on port 8080.
4. `terraform state show docker_container.nginx` - Inspected tracked infrastructure state.
5. `terraform destroy` - Cleaned up and removed created resources.
