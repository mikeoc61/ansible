# AWS EC2 Playbooks

## ec2.yml

Creates EC2 instance(s) based on specified AMI. 
First creates a security group, then creates EC2 instances based upon specified AMI
and then Tags EC2 instances. Once EC2 is running and SSH is available, installs Apache
Web server.

## ec2_down.,yml

Terminate EC2 instances associated with Tag used in ec2.yml
