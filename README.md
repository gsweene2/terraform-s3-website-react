# Create S3 Website Bucket, ACM for domain, Cloudfront, and Route 53 Zone and Record

-1. Clone or fork this repository.
0. Register a domain in Route53 AWS Console
1. Edit the `dev.tfvars` file to specify your domain and your desired bucket name
2. Configure your aws credentials on your machine
3. Run `terraform init -var-file=dev.tfvars`
4. Run `terraform plan -var-file=dev.tfvars`
5. Run `terraform apply -var-file=dev.tfvars`
6. Wait approximately 20 min for the terraform script to create your resources
7. Go to your domain in a browser
