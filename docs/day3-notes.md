# Day 3 Notes

## What I did
- Added the AWS provider configuration to Terraform
- Added a region variable in `variables.tf`
- Ran `terraform fmt`
- Ran `terraform init`
- Ran `terraform validate`

## What I learned
- Terraform uses providers to talk to external platforms like AWS
- The AWS provider tells Terraform which cloud platform to use
- Variables make the configuration more flexible than hardcoding values
- `terraform init` now prepares the project with the AWS provider plugin
- `terraform validate` confirms the Terraform configuration is structurally valid

## Current Terraform Files
- `main.tf`
- `variables.tf`

## Next step
- Configure AWS CLI with credentials
- Test AWS identity from the terminal
- Understand how Terraform uses AWS authentication