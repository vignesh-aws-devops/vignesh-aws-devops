# GitHub Profile

Welcome to my portfolio! Here you'll find detailed documentation about my skills, certifications, and projects as an AWS DevOps Engineer.

---

## **Table of Contents**
1. [About Me](#about-me)
2. [Core Skills](#core-skills)
3. [Certifications](#certifications)
4. [Highlighted Projects](#highlighted-projects)
5. [Contact Me](#contact-me)

---

### **About Me**
I am a passionate AWS DevOps Engineer with a proven track record of designing and implementing secure, scalable, and automated cloud solutions. With expertise in AWS services, DevOps tools, and automation practices, I thrive on solving complex challenges and delivering high-quality, cost-effective solutions.

I have extensive experience in:
- Architecting highly available and fault-tolerant systems using AWS best practices.
- Automating deployment pipelines with CI/CD tools for seamless application delivery.
- Building Infrastructure as Code (IaC) solutions with Terraform and AWS CloudFormation.
- Designing and deploying containerized applications using Docker and Kubernetes.
  
<sub>My commitment to continuous learning ensures that I stay ahead of the curve in emerging cloud technologies and DevOps trends, enabling me to bring innovative ideas to life.</sub>
---

## **Core Skills**
- AWS: Lambda, EC2, S3, RDS, CloudFormation, CodePipeline
- DevOps: CI/CD, Docker, Kubernetes, Terraform
- Programming: Python, SQL
- Cloud Automation and Infrastructure as Code (IaC)
- Scalable Cloud Architectures

---
- **AWS Certified SysOps Administrator – Associate**  
  *Issued: March 2025*  
- **AWS Certified Solutions Architect – Associate**  
  *Issued: December 2024*  
- **AWS Certified Cloud Practitioner**  
  *Issued: May 2022*

---

## **Highlighted Projects**

### **1. CI/CD Deployment Pipeline with CodeDeploy and CodePipeline**
- **Description:** Implemented an automated **CI/CD pipeline** to streamline the deployment process of applications from **Amazon S3** to **EC2 instances** using **AWS CodeDeploy** and **CodePipeline**. The pipeline includes the steps for building, testing, and deploying code in an automated fashion, reducing manual intervention and ensuring quicker updates to production environments.
- **Key Technologies:** CodePipeline, CodeDeploy, S3, EC2, SNS, CloudWatch, IAM
- **Outcome:** 
  - **Reduced Deployment Time**: Automated the entire deployment lifecycle, reducing deployment time by 40%.
  - **Error Handling**: Integrated **Amazon SNS** for deployment success/failure notifications and used **CloudWatch** for real-time monitoring.
  - **Rollback Mechanism**: Configured automatic rollback on failure to ensure minimal downtime.
  - **Continuous Integration**: Enabled continuous integration and delivery with frequent, reliable code pushes and deployments.

Check out my detailed LinkedIn post about this project [here](https://www.linkedin.com/posts/vignesh-aws-devops_devops-automation-cloudcomputing-activity-7284381142810607617-wzH5?utm_source=share&utm_medium=member_desktop). Feel free to share your thoughts and feedback!
You can access the full repository for this project on [GitHub](https://github.com/vignesh-aws-devops/end-to-end-cicd-pipeline/tree/main). Review the architecture, and collaborate!
 
### 2. **Automated Code Deployment Using Lambda and EventBridge**
- **Description:** Automated the deployment process for an application by integrating AWS Lambda, EventBridge, and EC2. The solution leverages an event-driven architecture to efficiently deploy new application code with minimal human intervention. AWS EventBridge schedules the deployment task every 15 minutes, allowing Lambda to monitor S3 for new code uploads. When a new file is detected, Lambda fetches, sorts, and compares timestamps with DynamoDB, ensuring that only the latest version of code is deployed. The solution then updates the application hosted on EC2, ensuring zero downtime and continuous delivery. The process also includes detailed logging in Amazon RDS for auditability and real-time tracking of deployment statuses.

- **Key Technologies:** Lambda, EC2, RDS, S3, DynamoDB, CloudWatch, EventBridge

- **Outcome:** 
  - Streamlined deployment processes and reduced deployment time by 40%, allowing for quicker rollouts of new code.
  - Enhanced scalability by automating the deployment across multiple instances, reducing human error and manual intervention.
  - Improved system reliability by automating health checks and logging deployment status to Amazon RDS, ensuring all deployment actions are fully auditable.
  - Enabled real-time tracking and faster response times to failures, improving the overall development lifecycle efficiency.

Check out my detailed LinkedIn post about this project [here](https://www.linkedin.com/posts/vignesh-aws-devops_aws-cloudcomputing-devops-activity-7277623826006384642-zVGZ?utm_source=share&utm_medium=member_desktop). Feel free to share your thoughts and feedback!
You can access the full repository for this project on [GitHub](https://github.com/vignesh-aws-devops/aws-eventbridge-lambda-deployment). Review the architecture, and collaborate!
    
### **3. Multi-Region Failover Architecture**
- **Description:** Designed and deployed a robust failover architecture across two AWS regions, leveraging AWS Route 53 for DNS failover, Application Load Balancers (ALBs) for traffic distribution, and Auto Scaling for automatic resource scaling based on demand. This architecture ensures high availability by directing traffic to the primary region under normal conditions and automatically failing over to the secondary region in case of an instance or regional failure. The architecture also incorporates SSL/TLS certificates from AWS Certificate Manager (ACM) for secure communication between clients and the application. The system was designed to maintain a seamless user experience with minimal downtime and fast recovery times.

- **Key Technologies:** Route 53, Auto Scaling, ALB, SSL/TLS, ACM, EC2, VPC

- **Outcome:** 
  - Achieved 99.99% uptime by designing a fault-tolerant architecture that balances traffic and ensures failover across regions.
  - Enhanced the user experience by ensuring minimal service disruption, even during regional outages.
  - Improved system resilience with automated scaling and health checks that ensure the application runs optimally across multiple regions.
  - Secured user data with SSL/TLS encryption, ensuring safe communication between the client and the application.
  - Demonstrated the ability to design scalable and highly available infrastructure using multiple AWS services.
 
Check out my detailed LinkedIn post about this project [here](https://www.linkedin.com/posts/vignesh-aws-devops_cloudcomputing-devops-highavailability-activity-7276608767062953986-iejC?utm_source=share&utm_medium=member_desktop). Feel free to share your thoughts and feedback!
You can access the full repository for this project on [GitHub](https://github.com/vignesh-aws-devops/aws-multi-region-failover-architecture). Review the architecture, and collaborate!

### **4. Secure EC2-to-S3 Communication Using VPC Endpoint**
- **Description:** Configured a private connection between EC2 instances and Amazon S3 using a VPC Endpoint, eliminating the need for public internet access. This setup ensures that all traffic between the EC2 instances and S3 is routed through the secure AWS private network, enhancing the security and reliability of data transfers. By removing public internet access, the solution reduces exposure to potential security threats, such as data breaches, and complies with strict network security policies. Additionally, this architecture improves data transfer speeds and lowers costs by avoiding the use of public IPs and internet bandwidth.

- **Key Technologies:** EC2, S3, VPC Endpoint, IAM Policies

- **Outcome:**
  - Ensured private, secure communication between EC2 instances and S3, preventing data from traversing the public internet.
  - Reduced potential attack surfaces by eliminating public access to S3 from outside the VPC.
  - Enhanced security through the use of IAM policies that govern access to the VPC Endpoint.
  - Achieved faster and more cost-effective data transfers, optimizing network performance and minimizing egress costs.
  - Improved overall system security and compliance by ensuring all data transfers remain within the AWS private network.

Check out my detailed LinkedIn post about this project [here](https://www.linkedin.com/posts/vignesh-aws-devops_aws-vpc-s3-activity-7281938765793697793-bgvv?utm_source=share&utm_medium=member_desktop). Feel free to share your thoughts and feedback!
You can access the full repository for this project on [GitHub](https://github.com/vignesh-aws-devops/cloud-security-with-vpc-endpoint-for-ec2-s3-communication). Review the architecture, and collaborate!


---

## **Contact Me**
- **Email:** vigneshkumarselvkumar@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/vignesh-aws-devops/
- **GitHub:** https://github.com/vignesh-aws-devops

---
