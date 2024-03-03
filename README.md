<!-- ABOUT THE ASSESSMENT -->
# HRS_Automation_Test

### Prerequisites:
* GitLab Repository: Create a GitLab repository for your Java application.
* AWS Account: Set up an AWS account with the necessary permissions for Lambda, EKS, or ECS.
* AWS CLI: Install and configure the AWS CLI on your CI/CD runner machine.

### CI/CD Pipeline Configuration:
* git_pipeline.yml includes building, testing, and deploying containerized Java applications in a serverless, AWS Lambda, or containerized setup

### AWS SAM Template:
* This file defines your AWS Lambda function and its resources.

### Additional Notes:
* Ensure you have the necessary AWS permissions for deploying Lambda functions, creating EKS or ECS clusters, and managing Docker images
* Customize the scripts and configurations according to your project structure, build tools, and deployment preferences.
* For EKS or ECS deployment, you'll need to provide additional scripts to create or update your clusters, services, and tasks.
