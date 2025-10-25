Installed Docker and ensured Docker is running.

Installed Terraform and verified version.

Created a project folder and wrote the main.tf configuration:

Pulled nginx:latest Docker image

Created and started a Docker container mapped to port 8080 → 80

Ran Terraform workflow commands:

terraform init → Initialized provider plugins

terraform plan → Reviewed execution plan

terraform apply → Provisioned Docker image & container

Verified container using docker ps and opened http://ec2PublicIP:8080

terraform state list → Checked managed resources

terraform destroy → Removed container and image

Saved all command outputs in logs.txt.
