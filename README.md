# Packer Example

Using Packer to automate the creation of AWS AMI. Packer automates the creation of any type of machine image. 

Instruction:
1. Download Packer from https://www.packer.io (depending on your OS)

2. Create example.json file and run the following command
     $ packer build -var 'secretkey=[secretkey]' -var 'accesskey=[accesskey]' example.json
