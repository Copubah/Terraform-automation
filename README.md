# How to use Terraform to automate Infrastructure on AWS
- Terraform is an open-source Infrastructure as Code (IaC) tool and it allows you to define, provision, and manage cloud infrastructure using declarative configuration files

## Infrastructure as a Code
- IaC is the process of managing and provisioning IT infrastructure using machine-readable defination file,you can manage infrastructure with configuration files rather than GUI
- IaC allows you define your infrastructure (servers, networks, databases, etc.) in code, enabling automation, repeatability, and consistency across your environments.

## Prerequisites
1. AWS CLI
2. Terraform
## Terraform Installation 
1. Install Terraform on Linux
   ## Update your system:
- sudo apt update && sudo apt upgrade -y
- curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
- sudo apt update
- sudo apt install terraform
- terraform version


## Terraform commands
- terraform init
- terraform plan
- terraform fmt
- terraform apply
- terraform destroy




