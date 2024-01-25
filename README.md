
![Screenshot (46)](https://github.com/satya19977/HighlyAvailable-3-Tier-Architecture/assets/108000447/06a457b2-2d8f-4daf-aa08-da8edcc95b84)


![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/9459884e-37d7-4835-b3ba-d8c36e29d244)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/df9307f1-a123-4915-9f82-1d30b80125f7)
![image](https://github.com/satya19977/Deploy-WordPress-Website-The-Traditional-Way/assets/108000447/618b0d44-9ce4-472c-ae66-5db24debfdb7)

VPC Setup:
 Configured a VPC for organizing and isolating resources effectively.
 Implemented two public subnets for EC2 instances with Auto Scaling Groups (ASG) to ensure redundancy and high availability.

Application Layer:
Established an application layer with two private subnets hosting EC2 instances managed by Auto Scaling Groups. This layer enhances security by isolating application servers from direct internet access.

Database Subnet:
Created a dedicated database subnet to host a Relational Database Service (RDS) instance, ensuring a secure environment for the database.

Auto Scaling Groups:
Implemented Auto Scaling Groups for both public and private subnets, allowing automatic adjustment of EC2 instances based on demand.

Internet-Facing ALB:
 Introduced an Internet-facing Application Load Balancer (ALB) to evenly distribute incoming internet traffic across EC2 instances in the public subnets. This enhances the availability and scalability of the application.

Internal Routing ALB:
Deployed an additional ALB for internal routing within the VPC, ensuring efficient and secure communication between different layers of the architecture. This ALB directs traffic to EC2 instances in the private subnets.

Security Measures:
Implemented security groups and Network Access Control Lists (NACLs) to control inbound and outbound traffic, enhancing the overall security posture of the infrastructure.

High Availability and Redundancy:
Designed the architecture with multiple availability zones for high availability, distributing resources across different zones to ensure resilience.
