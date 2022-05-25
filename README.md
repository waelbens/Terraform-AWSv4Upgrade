# Terraform-AWSv4Upgrade

Convert S3 bucket Terraform configuration after awsv4upgrade:

https://github.com/minamijoyo/tfedit

tfedit filter awsv4upgrade -u -f main.tf

terraform validate

terraform import aws_s3_bucket_*.ressource_id bucket_name
