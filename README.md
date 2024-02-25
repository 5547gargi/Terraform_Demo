
Search the AMI ID in the AWS and add it in the variables.tf PUBLIC_KEY_PATH ADD FULL PATH IN VARIABLES.TF-> -> command to generate the pub file -> ssh-keygen -f oregon-region-key-pair

Install terraform - https://www.terraform.io/downloads
Install Python if not already done https://www.python.org/downloads/
Install aws cli - https://docs.aws.amazon.com/cli/v1/userguide/install-macos.html
Create access key for terraform https://aws.amazon.com/console/
Use aws configure to configure the access keys [ aws configure command ]
Create a S3 bucket and add the name in config.tf
Define variables.tf and config.tf files.
Create Key pair -> ssh-keygen -f oregon-region-key-pair
Run - terraform init
terraform plan -out "file.plan"
terraform apply
terraform destroy
Define other necessary files.
