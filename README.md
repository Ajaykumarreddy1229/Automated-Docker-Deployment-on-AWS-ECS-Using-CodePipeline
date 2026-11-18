# Automated-Docker-Deployment-on-AWS-ECS-Using-CodePipeline

I have successfully worked on a hands-on AWS DevOps project to implement an automated CI/CD pipeline using GitHub and AWS services.

The main objective of this project was to automate the application build and deployment process using Docker containers.

**🔹 Technologies & AWS Services Used:**

- GitHub – Source Code Management
- Docker – Containerization
- Amazon ECR – Docker Image Storage
- Amazon ECS – Container Management
- AWS Fargate – Serverless Container Management
- AWS CodeBuild – Build Automation
- AWS CodePipeline – CI/CD Automation
- Application Load Balancer – Application Access
- IAM – Access Management

**🔹 Project Workflow:**

1. Created an EC2 instance using Amazon Linux 2023.
2. Installed Docker and Git.
3. Cloned the application from GitHub.
4. Created a Docker image using the Dockerfile.
5. Pushed the Docker image to Amazon ECR.
6. Created an ECS Cluster using AWS Fargate.
7. Configured Task Definition and ECS Service.
8. Configured an Application Load Balancer.
9. Created an AWS CodeBuild project.
10. Configured AWS CodePipeline with GitHub as the source.
11. Automated the deployment process.

**🔹 Final Outcome:**

Whenever I update the application code in GitHub and push the changes, AWS CodePipeline automatically triggers the process.

GitHub → CodePipeline → CodeBuild → Amazon ECR → Amazon ECS → Application Load Balancer

This project helped me understand how CI/CD automation works in real-time AWS DevOps environments.

**Continuous Learning | Hands-on Practice | AWS DevOps**

#AWS #DevOps #CICD #GitHub #Docker #AmazonECR #AmazonECS #AWSCodeBuild #AWSCodePipeline #Fargate #CloudComputing #DevOpsProjects
