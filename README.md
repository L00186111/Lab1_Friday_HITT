# Cloud Formation Stack for Friady_HITT small Company.
## Description
#### The purpose of this Lab1 is to describe the introduction of Cloud Computing where We are using AWS Service for Infrastructure as a Code for this Module. I will use a free AWS service for this module which provided by root user and connected with my local machine with AWS cloud service. We will make an ec2 instance with 1 of each subnet (private and public) with a secure gateway and show the routing table.
Amazon Web Service:
* An instance Elastic Compute Cloud (ec2) will be created using the AWS tool to use cloud formation stack. Its core service to control a virtual machine for AWS.
* Some of features will be add on to develop by AWS tool and format for live server to run. Such as subnet to accessible from internet.
* Further or external resources will use to do this lab1.need to create a Gateway access for security purpose.
* Self-Research and other notes provided by lecturer has been read through and uses as learning purpose. Using a Private Gateway(Nat gateway)service by AWS.

## Methods
* AWS service uses varies different type of method (API) tools to perform their connectivity to server for the business or the project.
* In our Lab1 project we will use ec2, IAM user, Network with VPC and Security connection via Gateway service.
* An account for AWS root user was created. The account enabled most features but did not allow groups people that add only specific task to access (in my case only S3 I give permission).
* This Individual tasks/lab1 were progressed through the AWS system over a number of days implementing a small application run by instance via VPC.

## Results
* To connect and API add for project has bee easier by AWS Servicer

* The creation of AWS ec2 instance and other network connection user tasks was successful and The AWS Cli remote connection makes easier to do the task
* The Lab1 project users to tasks was completed by AWS CLI and creating all connection made easier by small company project (in my case Friday_Hitt).

## Conclusion
Launching an EC2 instance using AWS CLI provides greater control and flexibility for automating cloud infrastructure. To understand of how AWS operates behind the scenes, whether you’re managing a single instance or deploying an entire fleet of servers, AWS CLI is an invaluable tool for streamlining your cloud operations. Further reading by (Kim ‘The DevOps Handbook’, 2021) indicated how cloud system and AWS Server tool help to do large task and control from local machine with cloud connection.Overall, in this practical lab1 work is bring knowledge we learn to apply in small project to do by real world Amazon Service. it was very complicated to do by myself as a new learner but found and learn a lots of new tools and technique to develop the DevOps engineer path.

## Reference
* K. Kim, J. Humble, P. Debois, J. Willis, N. Forsfren (2021). _The DevOps Handbook_, 2nd Edition. IT Revolution.
* “Use AWS CloudFormation Designer to create a basic web server” AWS Cloud Formation Guide. [online] Available at:
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/working-with-templates-cfn-designer-walkthrough-createbasicwebserver.html
[Accessed 24 Oct 2024].

* “What is AWS CloudFormation?” AWS Cloud Formation Guide. [online] Available at:
https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html [Accessed 24 Oct 2024].

*	“Welcome” AWS Cloud Formation and API Reference. [online] Available at:
https://docs.aws.amazon.com/AWSCloudFormation/latest/APIReference/Welcome.html [Accessed 24 Oct 2024].

* “What is AWS CloudFormation Hooks?” AWS CloudFormation Hooks User Guide. [online] Available at:
https://docs.aws.amazon.com/cloudformation-cli/latest/hooks-userguide/what-is-cloudformation-hooks.html
[Accessed 24 Oct 2024].

* R. Wagh (2024). “EC2 Essentials: Setup EC2, VPC, Subnet, Route Table, Internet Gateway, NAT Gateway, Jump host-Part 14” Youtube. [online] Available at:
https://www.youtube.com/watch?v=9NWTcumxf-4 
[Accessed 25 Oct 2024].

* Geeks for Geeks (2024). “Creating an EC2 Instance with AWS CLI: A Simple Tutorial”. [online] Available at:
https://www.geeksforgeeks.org/creating-ec2-instance-with-aws-cli/ 
[Accessed 25 Oct 2024].

## Appendices
Connected EC2 Instances with Security and have been 'ping' and 'curl' for tested
![EC2 Connect with Secuirity](https://github.com/user-attachments/assets/c2d839ae-444f-4253-8936-c7c4f2361145)

Running Public & Private EC2 Instances
![Running EC2 intances](https://github.com/user-attachments/assets/9144a5aa-0cfc-41d7-8086-f2e717a62d06)

Created Users IAM (Identity Access Management)
![Created Users IAM](https://github.com/user-attachments/assets/23b80420-7e63-4d11-8847-148a40e86a0b)

Created cloud formation stack
![Created cloud formation stack](https://github.com/user-attachments/assets/80ff75cc-65a1-467b-83ea-f73be718a513)

Created VPC (Virtual Private Connection)
![Created VPC](https://github.com/user-attachments/assets/12fc4992-b9bb-470e-a98a-de476c594f53)

Created Public and Private Subnet
![Created Subnet ](https://github.com/user-attachments/assets/eaf9347c-acbe-4624-aa52-bdbf55280ca2)

Created Inter Gateway and attached
![Created Inter Gateway ans attached](https://github.com/user-attachments/assets/f678f04a-ae21-49bb-8f84-19fb41cdf2db)

Created NatGateway for Private Subnet
![Created NatGateway](https://github.com/user-attachments/assets/d34a6c2a-15a9-403b-9d9f-5c53c7628896)

Created Route table & Associated
![Created Route table   Associated](https://github.com/user-attachments/assets/a508bd7f-760c-4bf5-9a0a-a569ebb496d1)

Created Demo group user access on s3
![Created Demo group user access on s3](https://github.com/user-attachments/assets/4ddabd74-14b9-4969-9a0d-70c4eacf8223)

Connect with Private route table with access
![connect with Private route table with access](https://github.com/user-attachments/assets/c7638f96-3ca0-4108-a264-b30d73cd4e75)

Public route save for all 
![Public route save for all ](https://github.com/user-attachments/assets/e60105a6-58be-47db-a9e4-ffe501cd0e85)



