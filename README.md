1. In iam-github-oidc, edit terraform.tfvars with your values

2. In terminal:
    cd iam-github-oidc
    terraform init
    terraform apply
    terraform output

3. Change the aws_region and availability_zone (add a or b at the end of given aws_region) as given to you, in tfvars of each environment (dev, preprod, and prod)

4. In each environment (dev, preprod, and prod), go to terraform.tf and change the backend bucket, dynamodb table names, and the region of the backend backend (this is NOT the aws_region given to you).

5. Share the project to GitHub