# DevOps_Project
Tools Used: Github,AWS,Jenkins,Docker

## Description: 
 1. Built a CI/CD Pipeline using Jenkins for automated testing and deployment.
 2. Containerized the application with Docker for consistent environments.
 3. Deployed on AWS for scalable cloud hosting.
 4. Integrated GitHub for version control and streamlined workflow.

# Docker_Commands
## Automated_Pipeline
```
ls
docker build -t auto .
docker images
```
## Docker_run_final
```
docker rm -f devops
docker run -d --name devops -p 80:80 auto
```

## AWS_DashBoard
![1  AWS Dashboard](https://github.com/user-attachments/assets/7c0da102-ccbb-450e-8750-257c1e412550)

## Jenkins_DashBoard
![6  Jenkins Dashboard](https://github.com/user-attachments/assets/0d5cc8f4-9de9-4951-9a86-8f09b9a97372)

## CI/CD_Pipeline
![9  Pipeline](https://github.com/user-attachments/assets/aca85f30-4429-4ddc-8d9d-b0139c0717a3)
