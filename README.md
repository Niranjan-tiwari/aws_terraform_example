Implemented terraform using AWS from scratch.
check this link - https://www.terraform.io/docs/commands/index.html
You can check here we have tried to automate a process using terraform commands.Please check main.tf file.
Create vpc
Create Internet Gateway
Create Custom Route Table
Create a Subnet 
Associate subnet with Route Table
Create Security Group to allow port for eg.22,80,443
Create a network interface with an ip in the subnet that was created in step 4
. Assign an elastic IP to the network interface created in step 7
 Create Ubuntu server and install/enable apache2 or nginx.
