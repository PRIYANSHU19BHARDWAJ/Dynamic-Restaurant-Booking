# AWS Deployment Guide

## 1. Provision EC2 with Terraform
```bash
cd terraform
terraform init
terraform apply
# 2. Configure Server with Ansible
cd ../ansible
ansible-playbook -i inventory playbook.yml
