**link**: https://d1.awsstatic.com/training-and-certification/Docs%20-%20Cloud%20Practitioner/AWS%20Certified%20Cloud%20Practioner_Sample%20Questions_v1.1_FINAL.PDF

<hr />

1. Why is AWS more economical than traditional data centers for applications with varying compute workloads?

A) Amazon Elastic Compute Cloud (Amazon EC2) costs are billed on a monthly basis.

B) Customers retain full administrative access to their Amazon EC2 instances.

C) Amazon EC2 instances can be launched on-demand when needed.

D) Customers can permanently run enough instances to handle peak workloads. 

    C seems like the most reasonable answer, instances can be launched on-demand and removed when they become redundant. Your usage can consistently match your workloads demands, therefore becoming more economical as you only pay for what you use. 

<hr />

2. Which AWS service would simplify migration of a database to AWS?

A) AWS Storage Gateway

B) AWS Database Migration Service (AWS DMS)

C) Amazon Elastic Compute Cloud (Amazon EC2)

D) Amazon AppStream 2.0


    AWS Storage Gateway is a hybrid cloud storage service, to allow on-premise access to virtually unlimited cloud storage. It has nothing to do with migration permanently. EC2 instances are for computing, and Amazon AppStream is a fully managed non-persistent application and desktop streaming service - nothing to do with data.

    AWS DMS is the only sensible answer. 

<hr />

3. Which AWS offerings enable customers to find, buy, and immediately start using software solutions in their AWS environment?

A) AWS Config

B) AWS OpsWorks

C) AWS SDK

D) AWS Marketplace

    AWS Config is for the assessment and evaluation of configurations of your AWS resources. OpsWorks is the use of Chef and Puppet to automate server configurations and deployments. SDK is a software-development kit, used within your code to progamatically access AWS resources. The marketplace is where you can find, buy, and immediately start using solutions.

<hr />

4. Which AWS networking service enables a company to create a virtual network within AWS?

A) AWS Config

B) Amazon Route 53

C) AWS Direct Connect

D) Amazon Virtual Private Cloud

    AWS Config, as mentioned earlier is for config management of servers. Route 53 is a DNS service, AWS Direct Connect is to establish a dedicated connection between a on-premise network and a AWS data center. Amazon Virtual Cloud does allow you to create a virtual network within AWS. 

<hr />

5. Which of the following is AWS's responsibility under the AWS shared responsibility model?

A) Configuring third-party applications.

B) Maintaining physical hardware

C) Securing application access and data

D) Managing custom Amazon Machine Images (AMIs)

    The shared responsibility model can be summarized as, the customer is responsible for security "in" the cloud, AWS is responsible for security "of" the cloud. Hence, B is the correct answer. 

<hr />

6. Which component of AWS global infrastructure does Amazon CloudFront use to ensure low-latency delivery?

A) AWS Regions

B) AWS Edge Locations

C) AWS Availability Zones

D) Amazon Virtual Private Cloud (Amazon VPC)

    AWS Regions are large geographical regions, with multiple Availability Zones within it. Amazon VPC, as seen earlier, is a way to provision a virtual network within the cloud, and AWS Edge Locations are available in most major cities around the world, specifically used by CloudFront (CDN) to distribute end-user content to reduce latency. It is where the frontend for the services access are located. B, is the correct answer. 

<hr />

7. How would a system administrator add an additional layer of login security to a user's AWS Management Console. 

A) Use AWS Cloud Directory

B) Audit AWS Identity and Access Management (IAM) roles

C) Enable multi-factor authentication

D) Enable AWS Cloud Trail

    Regarding an "additional layer", C, the enabling of multi-factor authentication is the only realistic answer. AWS Cloud Directory is a cloud-native directory for organizing hierarchies of data. IAM roles is identity and permissions management, and AWS Cloud Trail is a service to provide governance, compliance, operational auditing and risk auditing of your AWS account. 

<hr />

8. Which service can identify the user that made the API call when an Elastic Compute Cloud instance terminated?

A) Amazon CloudWatch

B) AWS CloudTrail

C) AWS X-Ray

D) AWS Identify and Access Management (AWS IAM)

    AWS IAM configurations would of enabled the user to make the call, but not help determine. AWS X-Ray is for analysis and debugging of production, distributed applications, AWS CloudTrail is for auditing (as described above). Amazon CloudWatch however is used for logging and monitoring of your applications. 

<hr />

9. Which service would you use to send alerts based on Amazon CloudWatch alarms?

A) Amazon SImple Notification Service (Amazon SNS)

B) AWS CloudTrail

C) AWS Trusted Advisor

D) Amazon Route 53

    Route 53 is a DNS service, Trusted Advisor is a tool to help provision resources following AWS best practices, CloudTrail is a auditing service. You would use Amazon SNS to send notifications in such an event. 

<hr />

10. Where can a customer find information about prohibited actions on AWS infrastructure. 

A) AWS Trusted Advisor

B) AWS Identify and Access Management (IAM)

C) AWS Billing Console

D) AWS Acceptable Use Policy

    The only sensible answer is D. Obviously. 