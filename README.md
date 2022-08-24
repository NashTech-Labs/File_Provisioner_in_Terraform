# Using File Provisioner in Terraform

## File Provisioner
The file type allows to transfer or copy the files or directories to the remote host. This provisioner supports ssh connection to support the file transferring over the remote servers. The source of files that need to be transferred and their destination in the created instance can be mentioned in the script.

In the block of code mentioned below, use the access key and secret key as per the aws configuration of your system
```
provider "aws"{
  region     = "us-east-1"
  access_key = "your_own_access_key"
  secret_key = "your_own_secret_key"
}
```
After this, run the following commands to complete the setup

`terraform init`

`terraform plan`

`terraform apply`
