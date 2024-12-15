# Lita-aws-EC2_project
A smartshop is an enterprise or platform designed to provide a seamless online shopping experience for customers.Their goal is to design and implement a scalable web infrastructure that can handle increased traffic, provide high availability, and ensure seamless customer experiences. This project document is the process of launching EC2 instance and deploying Apache web server on it. 
### Creation of VPC
VPC was created to house my resouces in the AWS environment.It is a virtual networking environment provided by AWS that allows users to launch AWS resouces in a virtual network that they define. The VPC has a CIDR of 10.0.00/16 Below is the image of my VPC image
 ![VPC](https://github.com/ObabireTobiloba/Lita-aws-EC2_project-smartshop/blob/VPC/VPC%20.png)
# Subnet Creation
I created 2 subnets, Public and Private Subnet
# Private Subnet (CIDR-10.0.2.0/24)
!{private subnet} 
# Public Subnet  (CIDR-10.0.1.0/24)
![public subnet](https://github.com/ObabireTobiloba/Lita-aws-EC2_project-smartshop/blob/VPC/subnet%20id.png)
# Configuration of the Network Access Control List (NACL)
Defining the inbound and outbound rules: Allow HTTP and SSH
![INBOUND RULES](https://github.com/ObabireTobiloba/Lita-aws-EC2_project-smartshop/blob/main/INBOUND%20RULES.png)
# Created Security Group
Security Group is a set of rules that define what traffic is allowed to flow in and out of your AWS resources.
Created security group with inbound rules to allow......traffic.

### Launch EC2 instances: I selected Amazon Linux 2(HVM) - Kernel 5.10, SSD Volume Type and i aslo created a keypair and i also used a public subnet for it.
!{ec2 instance} (/IMG
### Launching of Apache: I used command prompt in lauching this apache.
!{apache} (IMG_4316 and IMG _4311)
