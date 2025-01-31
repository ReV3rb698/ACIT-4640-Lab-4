# 4640-w4-lab-start-w25
## Caleb Campbell & Eric Chau
### ACIT 4640 - Set C

# Command used for generating key:
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```

# AWS SSO Login
```
aws sso login --profile <profile_name>
```

# Terraform Commands:
```
Terraform init => Prepare your working directory for other commands
Terraform fmt => Reformat your configuration in the standard style
Terraform validate => Check whether the configuration is valid
Terraform plan -out wk4-lab => Show changes required by the current configuration and outputs it into a file called "wk4-lab"
Terraform apply => Create or update infrastructure
Terraform destroy => Destroy previously-created infrastructure
```

# Resources Used to Configure the incomplete Blocks:
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/ami
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/subnet
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc_ipv4_cidr_block_association
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/internet_gateway
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/internet_gateway_attachment
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc_security_group_ingress_rule
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table_association

