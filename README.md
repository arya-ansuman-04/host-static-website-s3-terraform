# Host a Static Website on Amazon S3 using Terraform

## Project Overview

This project demonstrates Infrastructure as Code (IaC) by hosting a static website on Amazon S3 using Terraform.

Terraform automatically creates an S3 bucket, enables static website hosting, configures public access, applies a bucket policy, and uploads the website's HTML file.

## Technologies Used

- Amazon S3
- Terraform
- AWS CLI
- HTML
- Infrastructure as Code (IaC)

## Architecture

- AWS Region: Mumbai (ap-south-1)
- S3 Bucket: arya-capstone-static-website-2026
- Static Website Hosting enabled
- Public access configured for website content
- index.html uploaded using Terraform

## Deployment Steps

1. Configure AWS CLI credentials.

2. Initialize Terraform:

   ```bash
   terraform init
   ```

3. Validate the configuration:

   ```bash
   terraform validate
   ```

4. Preview the infrastructure:

   ```bash
   terraform plan
   ```

5. Deploy the infrastructure:

   ```bash
   terraform apply
   ```

## Website

URL: http://arya-capstone-static-website-2026.s3-website.ap-south-1.amazonaws.com

## Outcome

Successfully hosted a static website on Amazon S3 using Terraform. The website is publicly accessible through the S3 website endpoint.
