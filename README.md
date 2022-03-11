
# Aws Instance creation

For this Project aws account is created and attached the volumes  by using terraform 

## Acknowledgements

 - [Requried modules](https://registry.terraform.io/modules/terraform-aws-modules/ec2-instance/aws/latest)
 - [Aws ec2_instance](https://github.com/akhilpe/Terraform_Assignment_3.git)
 - [Volume provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/ebs_volume)


## Contributing


See `terraform.io` for ways to get started.

Please adhere to this project's `https://github.com/akhilpe/Terraform_Assignment_3.git`.


## Deployment

terraform init

```terraform commands
  terraform validate
  terraform refresh
  terraform plan
  terraform apply
```


## Features

- Create aws instance
- Create aws volume
- Attached the volume to the instance


## Appendix

Place the Access_key and Secret_key by using IAM policies
and it created aws instance and volumes and then volume going to attach the same instance.

