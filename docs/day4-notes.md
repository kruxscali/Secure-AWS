# Day 4 Notes

## What I did
- Configured AWS CLI with local credentials
- Set the default AWS region
- Verified AWS authentication using `aws sts get-caller-identity`

## What I learned
- AWS CLI stores credentials locally on the machine
- `aws sts get-caller-identity` is a safe way to verify who I am authenticated as
- Terraform can later use these AWS credentials through the AWS provider

## Next step
- Add my first AWS resource in Terraform
- Run `terraform plan`