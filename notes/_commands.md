---
tags:
    - tfcommands
---

# Commands list
```terraform
terraform init
```
used to initialise a working directory containing terraform config files. We would run this after writing a new Terraform configuration.
```terraform
terraform validate
```
used to validate terraform configuration files in the directory to ensure they're valid.     
```terraform
terraform plan
```
used for terraform to do a refresh to determine what actions are needed to achieve the desired state speicfied in the configuration files.  
```terraform
terraform apply
``` 
used to apply (create) the changes required to reach the desired state of the configuration.
```terraform
terraform destroy
```
used to destroy (delete) the terraform-managed infrastructure & asks for confirmation.
```terraform
terraform plan
```
used to preview the resources that are going to be deployed.
