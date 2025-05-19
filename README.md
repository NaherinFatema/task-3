Task 3: Infrastructure as Code (IaC) with Terraform

• Objective:
Use Terraform to provision a Docker container locally, demonstrating infrastructure as code.

• Technologies Used:
Terraform, Docker

• What Was Done:
• Installed Terraform and Docker on the local system
• Wrote a `main.tf` file to define a Docker provider and container resource
• Ran `terraform init` to initialize the project
• Used `terraform plan` to preview the infrastructure
• Applied the configuration using `terraform apply` to create the container
• Destroyed the infrastructure using `terraform destroy` after testing
• Verified container status and checked Terraform state files

• Files Included:
• main.tf – Terraform configuration to define Docker container
• terraform.tfstate – Terraform state file (if committed)
• Execution logs – CLI output showing terraform commands and responses

• Screenshots:
• Optional: Terminal output of apply, state, and destroy commands

• Interview Practice (from task):
• What is IaC
• What is Terraform state
• Plan vs Apply
• Terraform providers and resource dependencies
• Secret handling in Terraform

• Submission:
Code, execution outputs, and screenshots (if any) are included in the repository for review.

Naherin Fatema
