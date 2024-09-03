# Learn Terraform - Provision AKS Cluster

This repo is a companion repo to the [Provision an AKS Cluster tutorial](https://developer.hashicorp.com/terraform/tutorials/kubernetes/aks), containing Terraform configuration files to provision an AKS cluster on Azure.

* Installation Steps:
    1. sudo apt-get update
    2. sudo apt-get install -y software-properties-common
    3. curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
    4. sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
    5. sudo apt-get update && sudo apt-get install terraform
    6. terraform -v

* Download the Terraform Configuration files:
    1. Git Clone git clone https://github.com/hashicorp/learn-terraform-provision-aks-cluster
    2. cd learn-terraform-provision-aks-cluster
    3. Make changes to .tfvars file and aks-cluster.tf files
    4. Terraform init, plan and apply.
