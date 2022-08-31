# terraform
Infrastructure as code with terraform on AWS
Prerequisite in using the repo
i. install terraform
ii. Setup an AWS account
iii. Use any text editor - preferrably visual studio code

References 
https://registry.terraform.io/providers/hashicorp/aws/
What this Project tends to achieve
Create AWS EC2 instance using terraform
Create VPC( Virtual Private Cloud)
Create Internet Gateway
Create custom Route table
Create a subnet
Associate subnet with Route table
Create security group to allow port 22,80,443
Create Network Interface with IP in the subnet that was created #15
Assign an elastic IP to the network interface created in #18
create ubuntu server and install/enable Apache2

####################################################################################################
A key pair is required to be able to login via SSH into the EC2 instance, therefore we would login on the browser into AWS and and create a key pair 
