# 🛒 Responsive E-Commerce Website on Amazon Linux with Docker and Kubernetes

This repository contains the source code and documentation for a fully responsive e-commerce website, hosted on **Amazon Linux** and deployed using **Docker** and **Kubernetes**. The project integrates various AWS services such as **S3**, **ECR**, and **EKS**, with **NGINX** serving as the web server. The website is accessible via a Load Balancer, ensuring scalability, reliability, and seamless user experience.

![KUBERNETES-PRATHAM](https://github.com/user-attachments/assets/c1be802f-9d41-43f8-b5b3-78afe5e847c0)

## 🚀 **Project Overview**
- **Amazon Linux:** Base OS for Docker image creation, containing all website assets including `index.html`.
- **AWS S3:** Images and other media assets are stored in S3, with URLs dynamically linked in the website.
- **Docker & Amazon ECR:** Custom Docker image creation and storage in ECR for deployment.
- **Amazon EKS:** The application is deployed on an EKS cluster, utilizing EC2 instances.
- **NGINX:** NGINX is used as the web server, deployed using Kubernetes manifests.
- **Load Balancer:** The website is exposed to the internet via an AWS Load Balancer.

## 🔮 **Future Scope**
- **CI/CD Integration:** Automate the deployment process using AWS CodePipeline and CodeDeploy for continuous integration and continuous deployment.
- **Serverless Architecture:** Explore the possibility of transitioning to a serverless architecture using AWS Lambda and API Gateway for enhanced scalability and cost efficiency.
- **Database Integration:** Add a backend database service like Amazon RDS or DynamoDB to manage e-commerce transactions and user data.
- **Enhanced Security:** Implement AWS WAF and Shield for advanced security measures, protecting against common web exploits and DDoS attacks.
- **Monitoring and Logging:** Integrate AWS CloudWatch and ELK stack for real-time monitoring, logging, and alerting to ensure high availability and quick troubleshooting.

