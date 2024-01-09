# Terraform-Project

Install Terraform in Mac: 
--------------------------
brew tap hashicorp/tap

brew install hashicorp/tap/terraform

Terraform Project for creating EC2 instances on AWS:
-----------------------------------------------------
mkdir Terraform-Project

cd Terraform-Project

mkdir aws

cd aws

mkdir local_state

cd local_state

vim main.tf

terraform init

terraform plan

terraform apply

prompted question : yes

REMOTE BACKEND - Creating S3 bucket and Dynamo DB on AWS:
------------------

cd ..

mkdir remote_state

cd remote_state

vim main.tf

vim outputs.tf


terraform init

terraform plan

terraform apply

prompted question : yes

# make sure you are on the right aws account

pip install awscli

aws s3 ls

# If you don't set default region in your aws configuration, and you want to create the resources in region "us-east-1"

export AWS_DEFAULT_REGION=us-east-1

export AWS_REGION=us-east-1
