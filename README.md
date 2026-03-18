<img width="1007" height="638" alt="image" src="https://github.com/user-attachments/assets/cb227328-2de5-4617-89cb-2fc23c527c63" />


## AWS | VPC Peering 
AWS VPC infrastructure from a poorly configured default setup to a production-ready, secure, and scalable multi-tier architecture using Infrastructure as Code 


🚀 Basic Architecture
```
✅Multi-AZ Design: Resources distributed across 2 Availability Zones for high availability
✅Layered Security: Public/Private subnet separation with security groups and NACLs
✅Modular Infrastructure: Reusable Terraform modules for easy maintenance
✅Monitoring Ready: VPC Flow Logs and CloudWatch integration
✅Cost Optimized: Single NAT Gateway with proper routing
```


🧱  Advanced Features
```
Network Design:
VPC CIDR: 10.0.0.0/16
Public Subnets: 10.0.1.0/24 (AZ-a), 10.0.2.0/24 (AZ-b)
Private Subnets: 10.0.3.0/24 (AZ-a), 10.0.4.0/24 (AZ-b)

Security Layers:
Internet Gateway: Public internet access
NAT Gateway: Outbound internet for private subnets
Security Groups: Application-level firewall rules
NACLs: Subnet-level network controls
VPC Flow Logs: Network traffic monitoring

Compute Resources:
Web Servers: 2x EC2 in public subnets (Load Balanced)
App Servers: 2x EC2 in private subnets
Bastion Host: Secure access to private resources
```


🏗️ Deployment Options
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```




