# Custom AMI using Packer - Hashicorp Packer - CI/CD Pipeline

* Implemented CI/CD for Building AMIs with GitHub Actions
* Created AMI that can be shared between multiple AWS accounts
* AMI will setup the environment for the node.js and will install aws-codedeploy agent in 
  us-east-1 region.
* For this project AMI will be created in dev account and will be shared with prod account.

**Github Secrets**

1. `aws_access_key` (for dev account ghactions user)
2. `aws_secret_key`  (for dev account ghactions user)
3. `aws_region`  (us-east-1)
4. `aws_ami_users` (production aws account id)

**Command for validating and building AMI**

1. `packer validate ami.json  `  
2. `packer build ami.json`
  

**Download packer**

[Download Packer](https://www.packer.io/downloads)
update demo2




