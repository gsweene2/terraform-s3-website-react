# Create S3 Website Bucket, ACM for domain, Cloudfront, and Route 53 Zone and Record

1. Clone or fork this repository.
2. Register a domain in Route53 AWS Console
3. Edit the `dev.tfvars` file to specify your domain and your desired bucket name
4. Configure your aws credentials on your machine
5. Run `terraform init -var-file=dev.tfvars`
6. Run `terraform plan -var-file=dev.tfvars`
7. Run `terraform apply -var-file=dev.tfvars`
8. Wait approximately 20 min for the terraform script to create your resources
9. Go to your domain in a browser
