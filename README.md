# ☁️ Cloud_Craft_full-stack

Cloud_Craft is a full-stack cloud-native project featuring a Node.js backend application deployed on Google Cloud Platform. The project automates infrastructure provisioning with Terraform and uses CI/CD pipelines to ensure rapid delivery and scaling.

---

## 🧰 Tech Stack

- **Backend**: Node.js, Express
- **Database**: MySQL (Cloud SQL)
- **Cloud**: Google Cloud Platform (Compute Engine, Cloud SQL, Cloud DNS, Pub/Sub)
- **Infrastructure as Code**: Terraform, Packer
- **CI/CD**: GitHub Actions
- **Security & Testing**: Bcrypt for password hashing, Jest for unit testing

---

## 🚀 Key Features

- 🧾 User registration and login system with secure password hashing  
- 📩 Email verification using GCP Pub/Sub  
- ⚙️ Infrastructure provisioning using Terraform modules  
- 📦 Packaged VM images with Packer for immutable deployments  
- 🔄 CI/CD automation with GitHub Actions triggering VM updates  
- 📈 Load balancing and autoscaling for high availability  
- 🌐 DNS setup with A record mapping for domain exposure

---

## 🗂️ Deployment Overview

- Terraform provisions VPC, firewall rules, and Compute Engine instances
- Packer builds VM images which are deployed using CI/CD
- GitHub Actions automates the pipeline for every code push
- VM instances run the Node.js backend app and connect to Cloud SQL
- Domain routing handled via GCP DNS A record

---


## 🔗 Links

- 📂 GitHub Repo: [Cloud_Craft](https://github.com/poojapk0605/Cloud_Craft)  
- 🔗 [LinkedIn Project](https://www.linkedin.com/in/poojakannanpk/)

---

## 📄 License  
MIT License
