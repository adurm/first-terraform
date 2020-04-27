# Terraform

This repository will explain how to run the node sample app project.

### Prerequisites
- AMI (this can be built by following the nodesampleapp repository instructions here https://github.com/adurm/nodesampleapp )
- AWS
- Terraform
- AWS Credentials
- Git

### How to run
- Clone the repository
- In terminal, navigate to the root folder of this repo and execute the two commands:
```bash
terraform plan
terraform apply
```
- Once you see the following running in your terminal, your app is working properly
```bash
Your app is ready and listening on port 3000
```
- Navigate to http://(ip address of your ec2 instance):3000, for example http://1.2.3.4:3000
