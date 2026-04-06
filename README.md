# 🚀 Terraform Basics Lab — Infrastructure as Code on AWS

## 📖 Overview

This repository showcases my hands-on learning of **Terraform**, where I provisioned and managed AWS infrastructure using code.

Instead of manually creating resources through the AWS Console, this project demonstrates how **Infrastructure as Code (IaC)** enables automation, consistency, and version control in modern DevOps workflows.

---

## 🎯 Objectives

- Understand Infrastructure as Code (IaC)
- Install and configure Terraform
- Configure AWS CLI with credentials
- Provision AWS resources using Terraform
- Understand Terraform state management
- Modify and destroy infrastructure safely

---

## 🧠 What I Learned

- Terraform follows a **declarative approach** (define desired state)
- Difference between `plan`, `apply`, and `destroy`
- Importance of `terraform.tfstate`
- How Terraform tracks infrastructure changes
- Real-world DevOps workflow for provisioning infra

---

## 🏗️ Infrastructure Created

Using Terraform, I provisioned:

- 🪣 S3 Bucket (globally unique name)
- 💻 EC2 Instance (Amazon Linux 2 - t2.micro)

---

## 📁 Project Structure

.
├── main.tf                # Terraform configuration  
├── terraform.tfstate     # State file (ignored in Git)  
├── .terraform/           # Provider plugins  
├── .gitignore            # Ignore sensitive files  
└── README.md             # Project documentation  

---

## 🔧 Prerequisites

Make sure you have the following installed:

- Terraform
- AWS CLI
- AWS account with IAM credentials configured

---

## ⚙️ Setup & Usage

### 1️⃣ Clone Repository

[ git clone https://github.com/your-username/terraform-basics-lab.git ]  
[ cd terraform-basics-lab ]

---

### 2️⃣ Initialize Terraform

[ terraform init ]

---

### 3️⃣ Preview Execution Plan

[ terraform plan ]

---

### 4️⃣ Apply Configuration

[ terraform apply ]

Type `yes` when prompted.

---

### 5️⃣ Verify Resources

- Check S3 bucket in AWS Console  
- Check EC2 instance is running  

---

### 6️⃣ Destroy Infrastructure

[ terraform destroy ]

---

## 📊 Terraform Commands Explained

| Command                 | Description                          |
|------------------------|--------------------------------------|
| terraform init         | Initialize working directory         |
| terraform plan         | Preview infrastructure changes       |
| terraform apply        | Create/update resources              |
| terraform destroy      | Delete all resources                 |
| terraform show         | Show current state                   |
| terraform state list   | List tracked resources               |

---

## 📂 Terraform State (Important)

Terraform stores infrastructure details in:

- terraform.tfstate

### Contains:
- Resource IDs  
- Configuration details  
- Metadata & dependencies  

### ⚠️ Best Practices:
- Never edit state file manually  
- Never commit it to GitHub  
- Use remote backend in real projects  

---

## 📸 Screenshots

Add your screenshots here:

- Terraform Apply Output  
- AWS S3 Bucket  
- EC2 Instance Running  

---

## 🧹 Best Practices Followed

- Used `.gitignore` for sensitive files  
- Followed proper naming conventions  
- Used `terraform fmt` and `terraform validate`  
- Maintained clean and simple project structure  

---

## 💡 Key Takeaways

- Infrastructure can be fully automated using code  
- Terraform ensures repeatability and consistency  
- State management is critical in IaC  
- Easy to scale and modify infrastructure  

---

## 🔥 Future Improvements

- Add remote backend (S3 + DynamoDB)  
- Use Terraform modules  
- Create VPC and networking setup  
- Integrate with CI/CD pipelines  

---

## 🤝 Connect With Me

If you found this useful, feel free to ⭐ this repository and connect with me!

---

## 📢 Learning in Public

Started my Terraform journey 🚀  
Created AWS infrastructure using code and destroyed it in seconds.  
Infrastructure as Code finally makes sense!

#Terraform #AWS #DevOps #IaC #CloudComputing
