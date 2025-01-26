# AWS-cloud-devops-services
This repository provides a hands-on approach to implementing AWS Cloud DevOps services, showcasing how to use AWS tools to streamline development, deployment, and operational workflows.
# AWS Services Overview

This repository demonstrates my experience with various AWS services, showcasing practical examples for each. Below is a summary of the services included:

## 1. Amazon EC2 (Elastic Compute Cloud)  
EC2 allows you to rent virtual servers (instances) in the cloud. In this project, I've demonstrated the creation, management, and scaling of EC2 instances to handle dynamic workloads.

- Key Concepts: Instance types, security groups, key pairs, auto-scaling.

## 2. Amazon VPC (Virtual Private Cloud)  
VPC allows you to create isolated networks within AWS. This example demonstrates setting up subnets, routing tables, and private/public networks.

- Key Concepts: Subnets, Route Tables, VPN, NAT Gateways.

## 3. Security Groups and NACLs (Network Access Control Lists)  
Security groups control inbound and outbound traffic at the instance level, while NACLs control traffic at the subnet level. I've demonstrated their setup for securing resources.

- Key Concepts: Inbound/Outbound rules, stateless vs stateful filtering.

## 4. Amazon S3 (Simple Storage Service)  
S3 is an object storage service. I’ve included scripts to manage S3 buckets, upload/download files, and implement versioning and lifecycle policies.

- Key Concepts: Buckets, Object lifecycle, Encryption, Versioning.

## 5. AWS Lambda  
Lambda lets you run code without provisioning servers. This project shows how to trigger Lambda functions from various AWS services.

- Key Concepts: Event-driven architecture, triggers, scaling, function deployment.

## 6. Route 53  
Route 53 is AWS’s DNS and routing service. I demonstrate configuring DNS records and setting up routing for high availability.

- Key Concepts: Hosted Zones, Record Types, Health Checks.

## 7. Amazon CloudWatch  
CloudWatch helps you monitor AWS resources and applications in real-time. This example shows how to create alarms, monitor EC2 instances, and view logs.

- Key Concepts: Metrics, Alarms, Logs, Dashboards.

## 8. Amazon CloudFront  
CloudFront is a CDN (Content Delivery Network) service that speeds up the distribution of content globally. I have set up CloudFront to deliver static web content stored in S3.

- Key Concepts: Distributions, Edge Locations, Caching.

## 9. Cost Optimization  
This project focuses on techniques to optimize AWS costs, such as right-sizing EC2 instances, using Reserved Instances, and managing storage.

- Key Concepts: Cost Explorer, AWS Budgets, Trusted Advisor.

## 10. Boto3 (Python SDK)  
Boto3 allows you to automate AWS services using Python. I've included Python scripts to interact with various AWS resources programmatically.

- Key Concepts: API calls, Authentication, Resource management.

## 11. AWS CLI  
The AWS CLI provides a command-line interface for AWS services. I demonstrate how to use the CLI to automate tasks such as launching EC2 instances and configuring S3 buckets.

- Key Concepts: AWS CLI commands, Configuration, Profiles.

## 12. AWS CloudFormation (CFT)  
CloudFormation allows you to define infrastructure as code. I've written templates that describe and provision AWS resources like EC2, VPC, and S3.

- Key Concepts: YAML/JSON Templates, Stacks, CloudFormation Designer.

## 13. CI/CD with AWS Services  

### CodeCommit  
CodeCommit is a version control service. In this project, I showcase creating repositories, managing branches, and pushing commits.

### CodeBuild  
CodeBuild is used for compiling source code, running tests, and producing deployable artifacts. I set up build projects with customized buildspec.yml files.

### CodePipeline  
CodePipeline is a continuous integration and delivery service. I’ve set up pipelines that automate the build, test, and deployment phases of applications.
### CodeDeploy  
CodeDeploy automates the deployment of applications. This example showcases rolling updates and blue/green deployments using CodeDeploy.

## 14. Secrets Management  
Secrets Manager stores and manages sensitive information like passwords, API keys, etc. I've demonstrated using Secrets Manager to securely store and retrieve credentials.

## 15. AWS Config  
AWS Config provides a detailed view of configuration compliance. I've demonstrated how to set up AWS Config to track resource configurations and compliance.

## 16. Elastic Load Balancing (ELB)  
ELB automatically distributes incoming application traffic across multiple targets, such as EC2 instances. I've set up an application load balancer to distribute traffic.

- Key Concepts: Target Groups, Health Checks, SSL Termination.

## 17. Auto Scaling  
Auto Scaling adjusts the number of EC2 instances in response to changing demand. I’ve demonstrated setting up an Auto Scaling group with policies based on CPU utilization.

## 18. Amazon ECR (Elastic Container Registry)  
ECR is a fully managed Docker container registry. I demonstrate pushing and pulling Docker images to/from ECR.

- Key Concepts: Repositories, IAM policies, Docker images.

## 19. Amazon ECS (Elastic Container Service)  
ECS allows you to run Docker containers at scale. This example shows how to set up ECS clusters, task definitions, and services to deploy containerized applications.

## 20. Amazon EKS (Elastic Kubernetes Service)  
EKS provides a managed Kubernetes service. I’ve demonstrated deploying a multi-container application on EKS and managing scaling and deployments.

## 21. Terraform (Infrastructure as Code)  
Terraform allows provisioning and managing AWS resources with code. I've written Terraform configurations to set up a complete environment with EC2, VPC, and security.

- Key Concepts: Providers, Resources, State Files, Modules.

