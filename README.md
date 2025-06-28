# ☁️ CloudCraft – Full-Stack Node.js App with GCP & Terraform

CloudCraft is a backend application built from scratch using Node.js and deployed on Google Cloud Platform. It provisions cloud infrastructure using Terraform and implements secure CI/CD pipelines with auto-scaling VM deployment, startup scripts, and load balancing.

---

## 🧰 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MySQL (Cloud SQL)
- **Infrastructure:** Terraform, Packer, Google Cloud Platform
- **CI/CD:** GitHub Actions
- **Security & Auth:** bcrypt, JWT
- **Testing:** Jest
- **Messaging:** Pub/Sub for email verification

---

## 🛠️ Key Features

- 🔐 Role-based user authentication with hashed passwords (bcrypt)  
- 📧 GCP Pub/Sub integration for email verification  
- 🧱 Terraform + Packer for full GCP VM provisioning  
- 🚀 Startup scripts to automate application boot on VM launch  
- 📦 CI/CD with GitHub Actions to rebuild and redeploy new VM templates on push  
- ⚖️ Load balancing and autoscaling using instance templates  
- 🛡️ Secured infrastructure with IAM and GCP firewall rules

---

## ⚙️ Deployment Overview

- Terraform creates VPC, subnets, VM instance, Cloud SQL, Pub/Sub topics  
- Packer builds VM images that run the backend on startup  
- GitHub Actions triggers redeployment upon commit  
- Startup script installs dependencies and launches the Node app on instance boot  
- Cloud SQL manages persistent MySQL data storage

---

## 🔗 Links

- 📂 GitHub Repo: [Cloud_Craft](https://github.com/poojapk0605/Cloud_Craft)  
- 🔗 [LinkedIn Project](https://www.linkedin.com/in/poojakannanpk/)

---

## 📄 License  
MIT License
