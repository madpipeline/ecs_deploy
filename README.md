# ECS Deploy

This action uses Terraform to deploy your application to AWS ECS.

## Variables

| Variable name             | Default Value | Required |
| -------------             | ------------- | -------- |
| AWS_ACCESS_KEY            | N/A           | Yes      |
| AWS_SECRET_KEY            | N/A           | Yes
| TERRAFORM_WORKSPACE       | staging       | Yes      |
| APPLICATION_NAME          | N/A           | Yes      |
| APPLICATION_DOCKER_IMAGE  | N/A           | Yes      |
