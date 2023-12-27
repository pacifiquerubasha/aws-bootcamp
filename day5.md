# AWS Bootcamp Day 5 Summary

## TOPIC COVERED ==> CLOUD SECURITY

Cybersecurity that protects the data, applications and services associated with Cloud environments from both external and internal security threats
Cloud security helps:
  - Reduce impact of breach
  - Protect Networks & applications services against malicious data theft
  - Reduce human errors responsible for data leaks


In order to ensure effective level of security you should follow these steps:

### Step1 ⇒ MFA
  - Set the MFA (Multi-Factor Authentication) for the root account for security and IAM Users
  - You can set the MFA  through the IAM service (Identity and Access Management)


### Step2 ⇒ Create an organization Unit
  - AWS Organizations is a management service that helps you consolidate multiple AWS accounts into an organizational unit (OU) hierarchy
  - With AWS Organizations, you can apply consistent security policies and controls across all member accounts to ensure that all accounts adhere to the same set of rules.
  - The root user account represents the management account recommended to not have any applications but should be used to create the Organization Unit by created all other accounts 


### Step 3 ⇒ Enabling AWS Cloud Trail
  - AWS CloudTrail is a service that enables governance, compliance, operational auditing, and risk auditing of your AWS account. Helping monitor Data Security & Residence
  - It records and logs AWS API calls made on your account, providing a detailed history of actions taken by users, services, or automated processes 
  - Set Up / Create a Cloud Trail
  - Amazon Simple Storage Service (Amazon S3) is a scalable and highly durable object storage service provided by Amazon Web Services (AWS). S3 is designed to store and retrieve any amount of data from anywhere on the web and is widely used for a variety of use cases, ranging from simple storage of backup files to hosting static websites.


### Step 4 ⇒ Create IAM Users (Identity and Access Management) & IAM Roles, Policies
  - Set MFA for all your IAM Users as well
  - Attributes roles to a specific user 
  - Attach specific policies to a user or user group as well as setting necessarily permissions
Note: All services should be access using IAM (Identity and Access Management) users instead of the root account for security best practice in cloud environments


### Step5 ⇒ Enable AWS Organizations SCP
  - Service Control Policies (SCPs) help set fine-grained permissions and restrictions at the root level of users within your organization. 
  - It helps build control on what services and actions can be used and performed across the accounts within the AWS Organization.
  - Create new SCP policies based on your requirements
  - Attach SCP policies to specific AWS member accounts



### SECURITY BEST PRACTICES
Data Protection & Residency in accordance to Security Policy
Identity & Access MAnagement with Least Privilege
Governance & Compliance of AWS Services being Used
Global vs Regional Services
Compliant Services
Shared Responsibility of Threat Detection
Incident Response Plans to include Cloud



### AWS Well-Architected Framework
https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc&wa-guidance-whitepapers.sort-by=item.additionalFields.sortDate&wa-guidance-whitepapers.sort-order=desc
Pillars of the framework include:
 1. Operational Excellence
 2. Security
 3. Reliability
 4. Performance Efficiency
 5. Cost Optimization
 6. Sustainability

In order to create the AWS Well-Architected for the application the following steps need to be meet:
  - Define a workload for the application to build through the AWS Well-Architected Tool Service
  - The workload represents the applications, databases, servers, and other resources that work together to fulfill a specific function within your IT environment.
  - Review the workload created by answering a set of questions designed to assess the workload against best practices and guidelines in key areas. 
  - The questions are based on the pillars including: Operational Excellence, Security, Reliability, Performance Efficiency, Cost Optimization and Sustainability


### Homework Review ==> Create the Aws Cruddur (Architecting & Billing) LOGICAL DIAGRAM
Make sure to import the AWS Library





