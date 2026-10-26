\# Task 3: Infrastructure as Code with Terraform



\## Objective

Provision and manage a local Docker container using Terraform.



\## Tools Used

\- Terraform v1.16.6

\- Docker Desktop

\- Nginx Alpine



\## Implementation

1\. Configured the Docker provider in `main.tf`.

2\. Initialized Terraform using `terraform init`.

3\. Validated the configuration using `terraform validate`.

4\. Reviewed infrastructure changes using `terraform plan`.

5\. Created an Nginx Docker image and container using `terraform apply`.

6\. Verified the container using `docker ps`.

7\. Tested the Nginx web server at `http://localhost:8081`.

8\. Inspected Terraform state and cleaned up resources using `terraform destroy`.



\## Results

\- Terraform configuration validated successfully.

\- Nginx returned HTTP 200 OK.

\- Terraform successfully destroyed the two managed resources.



\## Learning Outcomes

\- Understanding Infrastructure as Code (IaC).

\- Using Terraform providers and resources.

\- Managing infrastructure state.

\- Planning, applying, verifying, and destroying infrastructure.



\## Files

\- `main.tf` — Terraform configuration.

\- `execution-logs.txt` — Execution evidence.

\- `.gitignore` — Excludes Terraform-generated files.

