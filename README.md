# 🚀 Terraform Lab — My Infrastructure as Code Learning Journey

## 📖 About This Repository

This repository documents my hands-on learning of **Terraform** as part of my DevOps journey.  
Here, I practice **Infrastructure as Code (IaC)** by building, modifying, and destroying real cloud infrastructure on AWS.

Each lab in this repo represents a practical step toward mastering how modern infrastructure is automated in real-world DevOps environments.

---

## 🎯 Purpose of This Repo

- Learn Terraform from basics to advanced
- Practice real-world infrastructure provisioning
- Build a strong DevOps portfolio
- Document learnings in a structured way
- Prepare for DevOps/Cloud interviews

---

## 🧠 What is Infrastructure as Code (IaC)?

Infrastructure as Code is the practice of managing infrastructure using code instead of manual processes.

Instead of clicking in AWS Console:
- We write configuration files
- Version control them using Git
- Apply them using tools like Terraform

👉 Result: Consistent, repeatable, and automated infrastructure

---

## ⚙️ Tools & Technologies Used

- Terraform
- AWS (S3, EC2, IAM, VPC - upcoming)
- AWS CLI
- Git & GitHub

---

## 📂 Repository Structure

.
├── 2026/  
│   ├── Day1/  
│   │   └── terraform-intro.md  
│   ├── Day2/  
│   └── ...  
├── terraform-projects/  
└── README.md  

---

## 📘 Labs Covered

### 📌 Terraform Basics
- Introduction to Terraform
- Understanding IaC
- Terraform lifecycle (init, plan, apply, destroy)
- Creating S3 bucket
- Launching EC2 instance
- Understanding state file

---

## 🔄 How I Approach Learning

For every lab, I follow this structure:

1. Understand the concept  
2. Write Terraform code  
3. Run commands and observe output  
4. Verify resources in AWS  
5. Document learnings  
6. Clean up resources  

---

## 🧪 Common Terraform Workflow

[ terraform init ] → Initialize project  
[ terraform plan ] → Preview changes  
[ terraform apply ] → Create resources  
[ terraform destroy ] → Clean up  

---

## 📊 Key Learnings So Far

- Terraform uses a **declarative approach**
- State file is the heart of Terraform
- Infrastructure can be version-controlled
- Easy to scale and replicate environments
- Automation reduces human errors

---

## ⚠️ Best Practices I Follow

- Never commit `.tfstate` files  
- Use `.gitignore` for sensitive data  
- Run `terraform fmt` before commit  
- Validate configs using `terraform validate`  
- Use meaningful naming conventions  

---

## 📸 Screenshots

Each lab includes:
- Terraform execution output  
- AWS Console verification  
- Resource creation proof  

---

## 🚀 Future Learning Plan

- Remote Backend (S3 + DynamoDB)
- Terraform Modules
- VPC & Networking
- Load Balancers & Auto Scaling
- Kubernetes Infrastructure using Terraform
- CI/CD Integration with Terraform

---

## 🎯 Goal

To become proficient in:
- Terraform
- Cloud Infrastructure Automation
- Real-world DevOps practices

---

## 🤝 Contribution / Feedback

This is a personal learning repository, but feedback and suggestions are always welcome!

---

## 📢 Learning in Public

I believe in learning by building and sharing.  
This repository is part of my journey to becoming a skilled DevOps Engineer.

---

⭐ If you find this helpful, consider giving it a star!
