# Day 5 Notes

## What I did
- Added my first AWS resource in Terraform
- Created a VPC resource block in `main.tf`
- Ran `terraform fmt`
- Ran `terraform validate`
- Ran `terraform plan`

## What I learned
- A Terraform `resource` block defines real infrastructure
- `terraform plan` shows what Terraform would do without actually doing it
- My current plan shows 1 resource to add, which is the VPC
- Terraform can now successfully read my configuration, use the AWS provider, and generate a real execution plan

## Why this matters
- This is the first point where my Terraform project is describing actual AWS infrastructure
- I now have the full chain from local code to AWS plan generation

## Next step
- Decide whether to run `terraform apply`
- Understand what Terraform state is
- Expand the VPC foundation with additional networking components later