Hands-on Lab: AWS Sample Architecture with Terraform for EFS, EBS

I want to share hands-on lab that shows how to design and implement AWS sample architecture using Terraform (Infrastructure as Code - IaC)

🌐  In this hands-on, demonstrated:
=>  how to provision EBS (Elastic Block Store), mount on Ubuntu and Windows Instances.
=>  how to provision EFS (Elastic File System), mount on Ubuntu Instance.
=>  how to provision VPC, Subnet, Internet Gateway, Route table, Security group.

🔥 There are 3 main parts:
=> main.tf: It includes 2 EC2 (Ubuntu, Windows), VPC, subnet, IGW, route table, security group implementation.
=> efs.tf: It includes EFS configuration for Ubuntu EC2.
=> ebs.tf: It includes EBS configuration for both Ubuntu and Windows EC2s.

GitHub code repo is in the comment below.  

💿 What are the EBS and EFS?
=> EBS (Elastic Block Store) is a block storage service for a single EC2 instance, similar to attaching an SSD or HDD, and is ideal for high-performance workloads like databases.
=> EFS  (Elastic File System) is a shared file storage service, like a scalable NFS, that can be accessed by multiple EC2 instances for distributed workloads.

🌟 What is  Terraform?
Terraform is a cloud-agnostic powerhouse for provisioning and managing cloud infrastructure. Here’s why it stands out:
=> Multi-Cloud Compatible: Works with AWS, Azure, Google Cloud.
=> Infrastructure Management: Version-controlled, testable, and repeatable infrastructure configurations.
=> Declarative Syntax: Define the desired state of your infrastructure easily.
=> Agentless: No need for extra software on managed instances.
=> Documentation: It has well-designed documentation
=> Modular Structure: It uses a modular structure.
=> State File: It tracks your infrastructure with TF state file.

Save this post for quick reference! 💡
