# Custom AMI using Packer - Hashicorp Packer - CI/CD Pipeline

* Implemented CI/CD for Building AMIs with GitHub Actions
* Created AMI that can be shared between multiple AWS accounts
* AMI will setup the environment for the node.js

**Environment variables/Github Secrets**

1. `aws_access_key`
2. `aws_secret_key`
3. `aws_region`
4. `aws_ami_users`

**Command for validating and building AMI**

1. `packer validate ami.json  `  
2. `packer build ami.json`

**Download packer**

[Download Packer](https://www.packer.io/downloads)

#update1

