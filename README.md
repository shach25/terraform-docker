1.Installed Docker and ensured Docker is running.

2.Installed Terraform and verified version.

3.Created a project folder and wrote the main.tf configuration

4.Pulled nginx Docker image

5.Created and started a Docker container mapped to port 8080 → 80

6.Ran Terraform workflow commands:

 terraform init → Initialized provider plugins

 terraform plan → Reviewed execution plan

 terraform apply → Provisioned Docker image & container

7.Verified container using docker ps and opened http://ec2PublicIP:8080

terraform state list → Checked managed resources

terraform destroy → Removed container and image

8.Saved all command outputs in execution logs.txt.
