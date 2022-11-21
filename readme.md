S3 Static Website Infrastructure

Setting up our Terraform components

bucket.tf - Creating a bucket to store state files
cdn.tf - Cloudfront for caching
hosted-zone.tf - aws_route53_zone
provider.tf
variables.tf - variables has defined
Terraform command to deploy our infrastructure
terraform init
This is going to install our providers and any other plugins we are using.

terraform plan
This will show us what infrastructure has changed and what will be added.

terraform apply
Finally, this command will run the plan and you will be prompted to type yes to apply the changes.