<img width="1007" height="638" alt="image" src="https://github.com/user-attachments/assets/cb227328-2de5-4617-89cb-2fc23c527c63" />


## AWS | Development 
AWS VPC infrastructure from a poorly configured default setup to a production-ready, secure, and scalable multi-tier architecture using Infrastructure as Code 


🚀 It’s especially helpful for:
```
✅Multi-AZ Design: Resources distributed across 2 Availability Zones for high availability
✅Layered Security: Public/Private subnet separation with security groups and NACLs
✅Modular Infrastructure: Reusable Terraform modules for easy maintenance
✅Monitoring Ready: VPC Flow Logs and CloudWatch integration
✅Cost Optimized: Single NAT Gateway with proper routing
```


🧱  Key Features
```
🐳 Runs entirely on Docker — no need for VM-based solutions like Minikube or K3s.
⚡ Fast startup and teardown — clusters can be created or destroyed in seconds.
🔁 Supports multi-node topologies — you can simulate real clusters easily.
🧩 Compatible with standard Kubernetes tooling — kubectl, Helm, etc., work out of the box.
🧪 Often used in CI/CD pipelines with tools like GitHub Actions and GitLab CI.
```


🏗️ Deployment Options
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```




