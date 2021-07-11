# DevOps-AWS

In the repository I am following AdminTurnedDevOps' tutorial to set up an environment that is using DevOps technologies and practices for deploying apps and cloud infrastructure to AWS.

## Technology Details

I am utilizing the following technologies and platforms to set up a DevOps environment

1. AWS
    - AWS will be used to host the application, cloud infrastructure, and any other services we may need to ensure the Uber app is deployed properly.
2. Python
    - Python will be used for the Uber app (it is written in Python) and some automation efforts that aren't in Terraform.
3. Terraform
   - Create an S3 bucket to store Terraform State files
   - Create an AWS ECR repository with Terraform
   - Create the EKS cluster
4. Docker
   - Create a Docker image
   - Store the Docker image in AWS ECR
5. Kubernetes
   - To run the Docker image that's created for the containerized Uber app. Kubernetes, in this case, EKS, will be used to orchestrate the container.
6. AWS CDK
   - TBD
7. CI/CD
   - TBD
8. Monitoring for applications and cloud services
   - TBD
9. GitHub
    - To store the application and infrastructure/automation code
10. Security best practices (DevSecOps)
    - Implement security best practices for the code you're writing and the cloud services you're building
11. Automated testing
    - TBD

This is currently a WIP.