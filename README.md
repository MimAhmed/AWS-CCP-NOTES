# AWS-CCP-NOTES 2020
This is a preparation notes for AWS CCP EXAM

# # AWS Certified Cloud Practitioner NOTES
### Official Link : [https://aws.amazon.com/certification/certified-cloud-practitioner/](https://aws.amazon.com/certification/certified-cloud-practitioner/)

## What is AWS?
Amazon Web Services (AWS) is the world’s most comprehensive and broadly adopted cloud platform, offering over 175 fully featured services from data centers globally. Millions of customers—including the fastest-growing startups, largest enterprises, and leading government agencies—are using AWS to lower costs, become more agile, and innovate faster.

## What is Cloud Computing ?
**Cloud computing** is **on-demand** delivery of different services through the Internet. These resources include tools and applications like data storage, servers, databases, networking, and software. ... As long as an electronic device has access to the web, it has access to the data and the software programs to run it.
**on-demand** *means you get it when you need it. you get it instantly.*
## What is a cloud model?
**Cloud** Computing is a **model** for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.
## Types of cloud computing

### Public cloud
A public cloud is owned by the cloud services provider (also known as a _hosting provider_). It provides resources and services to multiple organizations and users, who connect to the cloud service via a secure network connection, typically over the internet.
### Private cloud
A private cloud is owned and operated by the organization that uses the resources from that cloud. They create a cloud environment in their own datacenter and provide self-service access to compute resources to users within their organization. The organization remains the owner, entirely responsible for the operation of the services they provide.
### Hybrid cloud
A hybrid cloud combines both public and private clouds, allowing you to run your applications in the most appropriate location.

## Different Types of Colud Computing

### The Main Types of cloud services: IaaS, PaaS, serverless, and SaaS
## What is Infrastructure as a service (IaaS)?
**Infrastructure as a Service (IaaS)** hosts infrastructure on the public cloud and private cloud instead of in a traditional on-premises data center. The infrastructure is delivered to customers on demand while being fully managed by the service provider.
Popular **examples** of **laaS** DigitalOcean, Linode, Rackspace, **Amazon** Web Services (AWS), Cisco Metapod, Microsoft Azure, Google Compute Engine (GCE)
![IaaS](https://i.ibb.co/yVXmKjJ/infrastructure-as-a-service-iaas-diagram.png)

## What is  Platform as a service (PaaS)?
Platform as a service (PaaS) is a cloud computing model where a third-party provider delivers hardware and software tools to users over the internet. Usually, these tools are needed for application development. A PaaS provider hosts the hardware and software on its own [infrastructure](https://searchdatacenter.techtarget.com/definition/infrastructure). As a result, PaaS frees developers from having to install in-house hardware and software to develop or run a new application.
Popular **examples** of **PaaS** include AWS Elastic Beanstalk, Windows Azure, Heroku, Force.com, Google App Engine, and OpenShift.

![Pass](https://i.ibb.co/sQ8yJwS/platform-as-a-service-diagram.png)
## What is  Software as a service (SaaS)?
Software as a service (SaaS) is a software distribution model in which a third-party provider hosts applications and makes them available to customers over the Internet. SaaS is one of three main categories of cloud computing, alongside infrastructure as a service and platform as a service ([IaaS and PaaS](https://searchapparchitecture.techtarget.com/feature/Whats-the-difference-between-IaaS-and-PaaS-to-developers)).
![SaaS](https://i.ibb.co/5Yv6BG9/image.png)

These are several popular examples of SaaS, including: Google GSuite (Apps), **Dropbox**, Salesforce, Cisco WebEx, SAP Concur, and GoToMeeting.

## What is serverless computing or Function as a Service (FaaS)?

**Serverless computing**  lets you run application code without creating, configuring, or maintaining a server. The core idea is that your application is broken into separate  _functions_  that run when triggered by some action. This is ideal for automated tasks - for example, you can build a serverless process that automatically sends an email confirmation after a customer makes an online purchase.
## What is Shared Responsibility Model?
The shared responsibility model ensures cloud workloads are run securely and in a well-managed way. Depending on the service you are using, the cloud provider is responsible for some aspects of the workload management, and the customer or end user is responsible for other aspects of the workload management, and in some cases, both share a responsibility.

#### Customer = Responsibility For The Security **IN** The Cloud
#### AWS = Responsibility For The Security **OF** The Cloud
## What is AWS Organizations ?
It offers policy-based management for multiple AWS accounts. 
### Features  

 1. With Organizations, you can create groups of accounts and then apply policies to those groups.
 2. Organizations provides you a policy framework for multiple AWS accounts. You can apply policies to a group of accounts or all the accounts in your organization.
 3. AWS Organizations enables you to set up a single payment method for all the AWS accounts in your organization through consolidated billing.With consolidated billing, you can see a combined view of charges incurred by all your accounts, as well as take advantage of pricing benefits from aggregated usage, such as volume discounts for EC2 and S3.
 4. AWS Organizations, like many other AWS services, is eventually consistent.. It achieves high availability by replicating data across multiple servers in AWS data centers within its region.

## What is AWS Landing Zone?
 AWS Landing Zone is a solution that helps customers more quickly set up a secure, multi-account AWS environment based on AWS best practices. With the large number of design choices, setting up a multi-account environment can take a significant amount of time, involve the configuration of multiple accounts and services, and require a deep understanding of AWS services.
 Watch How AWS Landing Zone Woks : https://www.youtube.com/watch?v=d6mMyhgqIZE
## What is AWS Control Tower?
AWS Control Tower is a service that offers the easiest way to set up and govern a new, secure, multi-account AWS environment. It establishes a landing zone that is based on best-practices blueprints, and enables governance using guardrails you can choose from a pre-packaged list. The landing zone is a well-architected, multi-account baseline that follows AWS best practices. Guardrails implement governance rules for security, compliance, and operations.

 Watch How AWS Control Tower Woks :  https://www.youtube.com/watch?v=2t-VkWt0rKk
## AWS Cloud Development Kit (CDK)
The AWS Cloud Development Kit (AWS CDK) is an open source software development framework to model and provision your cloud application resources using familiar programming languages.
Video : [More About CDK](https://youtu.be/bz4jTx4v-l8)

## AWS Services ?
***Some Popular AWS Services You Need To Know For AWS Certified Cloud Practitioner***
## AWS IAM
### What is IAM Role ?
An IAM _role_ is an IAM identity that you can create in your account that has specific permissions. An IAM role is similar to an IAM user, in that it is an AWS identity with permission policies that determine what the identity can and cannot do in AWS. However, instead of being uniquely associated with one person, a role is intended to be assumable by anyone who needs it. Also, a role does not have standard long-term credentials such as a password or access keys associated with it. Instead, when you assume a role, it provides you with temporary security credentials for your role session. 
Know More About IAM [Here]([https://aws.amazon.com/iam/features/](https://aws.amazon.com/iam/features/))

## AWS EC2
Amazon  [EC2](https://aws.amazon.com/ec2/)  (Elastic Compute Cloud), one of Amazon Web Services’ most well-known services, offers businesses the ability to run applications on the public cloud.

### Is EC2 a Virtual Machine?

Developers can create instances of virtual machines and easily configure the capacity scaling of instances using the EC2 web interface.

### What is the Use of AWS EC2?

EC2 also allows users to build apps to automate scaling according to changing needs and peak periods, and makes it simple to deploy virtual servers and manage storage, lessening the need to invest in hardware and helping streamline development processes.
To Know About EC2 Visit [Here]([https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html))
## Amazon VPC

## Amazon RDS
## Amazon S3
## Amazon CloudFront
## Amazon SNS
## Amazon Elastic Beanstalk
## AWS Lambda
### AWS Auto Scaling






# Foundation Courses  


**Amazon Official Course:** https://aws.amazon.com/training/course-descriptions/cloud-practitioner-essentials/
1.  Setting up an account with AWS:  [https://www.youtube.com/watch?v=WviHsoz8yHk&feature=youtu.be](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DWviHsoz8yHk%26feature%3Dyoutu.be)
2.  Get introduced to AWS Services:  [https://www.youtube.com/watch?v=Z3SYDTMP3ME&t=46s](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DZ3SYDTMP3ME%26t%3D46s)
3.  AWS VPC Masterclass:  [https://www.youtube.com/watch?v=LX5lHYGFcnA&t=2599s](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DLX5lHYGFcnA%26t%3D2599s)
4.  Amazon VPC (Simple Learn) : https://www.youtube.com/watch?v=fpxDGU2KdkA
5.  AWS Certified Cloud Practitioner:  [https://www.youtube.com/watch?v=3hLmDS179YE&t=1406s](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D3hLmDS179YE%26t%3D1406s)
6. AWS Networking Fundamentls : https://www.youtube.com/watch?v=hiKPPy584Mg
7.  AWS Certified Solutions Architect Associates:  [https://www.youtube.com/watch?v=Ia-UEYYR44s&t=36943s](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DIa-UEYYR44s%26t%3D36943s)
8.  AWS Certified Developer Associates:  [https://www.youtube.com/watch?v=RrKRN9zRBWs&t=14s](https://slack-redir.net/link?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DRrKRN9zRBWs%26t%3D14s)

## Exam Preparation
[https://aws.amazon.com/certification/certification-prep/](https://aws.amazon.com/certification/certification-prep/)
https://www.quora.com/How-do-I-prepare-for-the-AWS-certification-cloud-practitioner-level
[https://towardsdatascience.com/ace-your-first-aws-certification-in-10-days-f6b2b7cbea34](https://towardsdatascience.com/ace-your-first-aws-certification-in-10-days-f6b2b7cbea34)
[https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf](https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf)

# Blogs
https://aws.amazon.com/types-of-cloud-computing/
https://docs.microsoft.com/en-us/learn/paths/explore-microsoft-azure-cloud-concepts/
https://aws.amazon.com/compliance/shared-responsibility-model/
https://searchcloudcomputing.techtarget.com/definition/Platform-as-a-Service-PaaS
https://avinetworks.com/glossary/infrastructure-as-a-service-iaas/
https://searchcloudcomputing.techtarget.com/definition/Software-as-a-Service
https://mindmajix.com/top-aws-services
https://tutorialsdojo.com/aws-organizations/
https://www.simplilearn.com/aws-certification-cost-article
https://www.whizlabs.com/blog/top-aws-services/
https://www.sumologic.com/insight/what-is-aws-ec2/
https://www.mitocgroup.com/blog/my-architecture-aws-control-tower-vs-aws-landing-zone/
https://docs.aws.amazon.com/vpc/latest/userguide/how-it-works.html
