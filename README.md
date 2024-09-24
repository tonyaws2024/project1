# MY FIRST ASSIGNMENT 

## Description

## Assignment 1

For my first assignment in the Amazon Web Services it was expected of me to

* Host a website in S3 bucket
* Use Cloudformation to Launch an Amazon EC2 Web Server, create a remote access and install python and Docker using the remote access
* Deploy SQL Server Databases on Amazon RDS
* Build a Serverless Processing System
* Deploy a Simple Python Web Application with AWS Elastic Beanstalk

### S3 Bucket

Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Millions of customers of all sizes and industries store, manage, analyze, and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize and analyze data, and configure fine-tuned access controls to meet specific business and compliance requirements.

![Image Alt](https://github.com/tonyaws2024/project1/blob/c4d033b75fcd18f99955df3fe2463a4aa3dac69c/Screenshot%20of%20S3%20buckets.jpg)

#### HTML script for static website hosted in S3

![Image Alt](https://github.com/tonyaws2024/project1/blob/44169d5bf4c689c4046600647e7cfbe8d11af3a1/HTML%20Script%20for%20the%20static%20website%20hosted%20in%20S3%20bucket.jpg)

### EC2

Amazon Elastic Compute Cloud (Amazon EC2) provides on-demand, scalable computing capacity in the Amazon Web Services (AWS) Cloud. Using Amazon EC2 reduces hardware costs so you can develop and deploy applications faster. You can use Amazon EC2 to launch as many or as few virtual servers as you need, configure security and networking, and manage storage. You can add capacity (scale up) to handle compute-heavy tasks, such as monthly or yearly processes, or spikes in website traffic. When usage decreases, you can reduce capacity (scale down) again.

![Image Alt](https://github.com/tonyaws2024/project1/blob/9eaa32aebb8b4cb8eaa1dee318feafcca165a99d/Screenshot%20of%20EC2%20instances.jpg)

### IAM

An IAM role is an IAM identity that you can create in your account that has specific permissions. An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it. Also, a role does not have standard long-term credentials such as a password or access keys associated with it. Instead, when you assume a role, it provides you with temporary security credentials for your role session. You can use roles to delegate access to users, applications, or services that don't normally have access to your AWS resources

![Image Alt]()

#### Cloud Formation Code for launching the EC2 web server

![Image Alt](https://github.com/tonyaws2024/project1/blob/9cee273fcb596ae2448d931a1c776a49ad1d3956/Cloud%20Formation%20Code%20for%20EC%202.jpg)

#### Remote Desktop Access to EC2 instance launced with cloudformation

You can connect to Amazon EC2 instances created from most Windows Amazon Machine Images (AMIs) using Remote Desktop. Remote Desktop uses the Remote Desktop Protocol (RDP) to connect to and use your instance in the same way you use a computer sitting in front of you.

I used a key pair named **myproject1.pem** to generate a password for the remote desktop connection to my EC2 server

![Image Alt](https://github.com/tonyaws2024/project1/blob/df8624f3e5297165a9f66aea88b0b746fac1cd86/RDP%20connection.jpg)

### Serverless Systems

Serverless computing is an application development model where you can build and deploy applications on third-party managed server infrastructure. All applications require servers to run. But in the serverless model, a cloud provider manages the routine work; they provision, scale, and maintain the underlying infrastructure. The cloud provider handles several tasks, such as operating system management, security patches, file system and capacity management, load balancing, monitoring, and logging. As a result, developers can focus on application design and still receive the benefits of cost-effective, efficient, and massively scalable server infrastructure.





