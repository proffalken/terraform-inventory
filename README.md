terraform_inventory [![Build Status](https://travis-ci.org/bandwidthcom/terraform-inventory.svg)](https://travis-ci.org/bandwidthcom/terraform-inventory)
=========

Create an Ansible inventory file from a Terraform state file.

This tool was written so that Terraform can be used for only creating infrastructure and then Ansible for configuration management.

#### Example
```
tinventory --map=aws_instance.web:web aws_instance.web.1:db ./inventory
```
