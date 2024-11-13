## Frequently used Terraform Commands with Explanation

#### 1. terraform version

`Explanation:` This command displays the version of Terraform currently installed on your system. It's a quick way to check the installed version and make sure it matches the version you intend to use.
```
terraform version
```
#### 2. terraform init

`Explanation:` This command initializes and Prepares your working directory. It downloads the necessary provider plugins and sets up the backend configuration defined in your terraform block.
```
terraform init
```
#### 3. terraform providers

`Explanation:` This command shows a list of installed provider plugins along with their versions. Providers are responsible for managing resources on various cloud platforms.
```
terraform providers
```
#### 4. terraform fmt

`Explanation:` This command automatically formats your Terraform configuration files to follow a consistent style. It helps in maintaining a clean and readable codebase.
```
terraform fmt
```
#### 5. terraform validate

`Explanation:` This command validates the syntax and structure of your Terraform configuration files. It checks for any errors or issues in your code.
```
terraform validate
```
#### 6. terraform plan

`Explanation:` This command generates an execution plan. It compares the current state of your infrastructure with the desired state defined in your Terraform files. It shows you what changes Terraform will make to achieve the desired state without actually making those changes.
```
terraform plan
```
#### 7. terraform apply

`Explanation:` This command applies the changes defined in your Terraform configuration to the infrastructure. It creates, updates, or deletes resources as necessary to match the desired state.
```
terraform apply
```
#### 8. terraform output

`Explanation:` This command displays the values of `output variables` defined in your Terraform configuration. Output variables provide information about the resources created or managed by Terraform.
```
terraform output
```
#### 9. terraform show

`Explanation:` This command displays the current state of your infrastructure as recorded in the Terraform state file. It provides a human-readable representation of the resources that Terraform is managing, along with their attributes and current values.
```
terraform show
```
#### 10. terraform destroy

`Explanation:` This command is used to destroy the infrastructure defined in your Terraform configuration. It deletes all the resources that were created using Terraform.
```
terraform destroy
```
#### 11. terraform import

`Explanation:` The terraform import command allows you to import existing infrastructure resources into your Terraform state. This is useful when you have resources that were not initially created and managed by Terraform, but you want to start managing them using Terraform moving forward.
```
terraform import
```
#### 12. terraform refresh

`Example:` Let's say you have an AWS EC2 instance defined in your configuration. If someone manually stops or starts the instance using the AWS Management Console, Terraform wouldn't be aware of this change until you run terraform refresh. Once you do, Terraform will update its state to match the current status of the instance.
```
terraform refresh
```
