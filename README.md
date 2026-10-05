# DevOps Task 3 - Terraform + Docker + Nginx

## Task: Deploy nginx:alpine container using Terraform on port 8080

### Code: main.tf
- Used kreuzwerker/docker provider
- Pulled nginx:alpine image
- Created container devops-task3-container (80 -> 8080)

### Proof
1. `terraform apply` success - 2 resources added
2. `localhost:8080` - Welcome to nginx! page running
3. `docker ps` - container running

### Commands Used
.\terraform init
.\terraform plan
.\terraform apply -auto-approve
docker ps

### Screenshots Attached
- apply complete
- nginx welcome page

Done by: Soundar
Date: 10/05/2026
