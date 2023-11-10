# Auto Deploy Web Application
## Project Overview

This project exemplifies advanced proficiency in Continuous Integration/Continuous Deployment (CI/CD) principles, deployment strategies, configuration management, and structured logging for cloud-based software products. It embodies industry-best practices and utilizes robust tools to automate the build, test, and deployment processes, showcasing a professional approach to software delivery.

## Objectives

- **CI/CD:**
  - Articulate the core principles and advantages of CI/CD in achieving automated and efficient deployment workflows for cloud-based software with circleCi.

- **Deployment Strategies:**
  - Design and implement CI/CD pipelines that adhere to Continuous Delivery practices, employing deployment strategies for reliable software deployment.

- **Configuration Management:**
  - Utilize Ansible, a powerful configuration management tool, to ensure consistent and reproducible deployments to cloud-based servers.

- **Structured Logging:**
  - Implement structured logging methodologies to identify and diagnose critical server errors, enhancing monitoring capabilities.

## Project Architecture

The project's architecture adheres to industry standards, utilizing a combination of AWS services, Circle CI for CI/CD, Ansible for configuration management, and Prometheus for monitoring.

## Project Structure

- **docs/:**
  - Holds project documentation, including architecture diagrams and additional resources.

- **src/:**
  - Contains source code for the application, organized into backend and frontend components.

- **scripts/:**
  - Houses deployment, monitoring, and infrastructure creation scripts.

- **tests/:**
  - Includes unit tests and scripts for vulnerability testing.

- **.circleci/:**
  - Encompasses configuration files for CircleCI workflows and jobs.

## Getting Started

1. **Clone the Repository:**
```bash
git clone https://github.com/Blessing-AkP/Auto-Deploy-App-Project-3.git
```

2. **Setting Up AWS Resources:**
   Use AWS CLI and CloudFormation for infrastructure creation.
```bash
aws cloudformation create-stack --stack-name my-stack --template-body file://cloudformation_template.yaml
```

3. **Deploying Backend on EC2:**
   Leverage CircleCI jobs to deploy the application backend to EC2 instances.
```bash
circleci config validate # Validate CircleCI configuration
circleci local execute # Run CircleCI jobs locally
```

4. **Monitoring with Prometheus:**
   Establish and monitor application metrics using Prometheus.
```bash
docker-compose up -d prometheus # Start Prometheus server
```

5. Access Deployed Components:
    Access the deployed components via the provided public URLs

##Built With
Circle CI: Cloud-based CI/CD service
Amazon AWS: Cloud services
AWS CLI: Command-line tool for AWS
CloudFormation: Infrastructure as code
Ansible: Configuration management tool
Prometheus: Monitoring tool




