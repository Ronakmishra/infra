# Terraform AWS Infra

This project sets up and manages AWS infrastructure using **Terraform**. The configuration files provided define the resources and variables needed to create and manage an environment in AWS.

## Setup Instructions

1. Initialize the Terraform project:

   ```bash
   terraform init

   ```

2. Format Terraform files

   ```bash
   terraform fmt

   ```

3. Validate the Terraform configuration

   ```bash
   terraform validate

   ```

4. Plan the infrastructure changes

   ```bash
   terraform plan

   ```

5. Apply the Terraform configuration

   ```bash
   terraform apply

   ```

6. Destroy the infrastructure

   ```bash
   terraform destroy

   ```

7. Import Certificate

   ```bash
   aws acm import-certificate ^
       --certificate fileb://C:\Users\ronak\Desktop\Downloads\demo_ronak.me\demo_ronak_me.crt ^
       --private-key fileb://C:\Users\ronak\Desktop\Downloads\demo_ronak.me\privatekey.pem ^
       --certificate-chain fileb://C:\Users\ronak\Desktop\Downloads\demo_ronak.me\demo_ronak_me.ca-bundle ^
       --region us-east-1 ^
       --profile demo

   ```

8. List the certificate

   ```bash
   aws acm list-certificates --region us-east-1 --profile demo

   ```
