<h3 align="center"><strong>AWS Lambda Container Deployment Track</strong></h3>

---
### Objective
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Deploy the containerized microservices using AWS Lambda with container images, demonstrating your skills in serverless architecture, containerization, and AWS services.

---
### Technical Requirements
1.	#### Infrastructure as Code (Terraform)
    *	Provision a VPC with public and private subnets (if needed)
    *	Set up Lambda functions configured for container image deployment
    *	Configure necessary IAM roles and security groups
    *	Set up an ECR repository for your container images
    *	Create an API Gateway to trigger your Lambda functions
  
2.	#### Containerization
    *	Create a Dockerfile for the microservices, optimized for Lambda
    *	Build and push the Docker image to ECR

3.	#### Lambda Configuration
    *	Configure Lambda functions to use container images
    *	Set up appropriate memory and timeout settings
  	
4.	#### CI/CD (GitHub Actions)
    *	Implement a workflow for Terraform (lint, plan, apply)
    *	Create a workflow for building and pushing Docker images
    *	Implement a workflow for updating Lambda functions

5.	#### Monitoring and Logging
    *	Set up CloudWatch for Lambda logging and metrics
    *	(Bonus) Implement X-Ray for distributed tracing

---

### Deliverables
1.	#### GitHub repository containing:
    *	Terraform code
    *	Dockerfiles optimized for Lambda
    *	GitHub Actions workflows
    *	Application code (provided microservices)

2.	#### Documentation:
    *	Architecture diagram
    *	Setup and deployment instructions
    *	Monitoring and logging overview

---

### Evaluation Criteria
1.	Lambda configuration and security
2.	API Gateway setup and integration
3.	CI/CD pipeline efficiency and reliability
4.	IaC quality and modularity
5.	Containerization best practices for Lambda
6.	Monitoring and logging effectiveness
7.	Documentation clarity and completeness
