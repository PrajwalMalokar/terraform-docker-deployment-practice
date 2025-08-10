# Terraform Docker Container Provisioning

## Objective
Use Terraform to provision a Docker container running nginx locally.

## Tools
- Terraform
- Docker

## Steps
1. Initialize: `terraform init`
2. Plan: `terraform plan`
3. Apply: `terraform apply`
4. Verify: Visit `http://localhost:8081`
5. Destroy: `terraform destroy`

## Output
- Nginx container runs on port 8081

## Commands for Reference

```bash
# Initialize Terraform
terraform init

# Plan the deployment
terraform plan

# Apply the configuration
terraform apply

# List the resources in state
terraform state list

# Destroy the resources when done
terraform destroy
```
