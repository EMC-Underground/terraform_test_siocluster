### Deploy Swarm Nodes using Terraform

First create a `terraform.tfvars` file using the example as the template
Add public SSH key to authorized_keys

```shell
terraform init \
-backend-config="access_key=<ACCESS_KEY_LOCATED_IN_TERRAFORM.tfvars>" \
-backend-config="secret_key=<SECRET_KEY_LOCATED_IN_TERRAFORM.tfvars>"

terraform apply
```
