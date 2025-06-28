☁️ Cloud_Craft – Full-Stack Infrastructure-as-Code Project on GCP
Cloud_Craft is a backend-driven infrastructure project that demonstrates how to build and deploy a scalable, production-grade Node.js application on Google Cloud using Terraform and automation tools.

🧰 Tech Stack
Backend: Node.js, Express.js, Jest

Database: Google Cloud SQL (MySQL)

Infrastructure as Code: Terraform

Automation & Imaging: Packer, GitHub Actions

Cloud Services: Google Compute Engine, Pub/Sub, Cloud DNS

Security: Bcrypt (password hashing), GCP IAM

High Availability: Load Balancing, Instance Templates, Managed Instance Groups

🛠️ Key Features
✅ User registration & login with secure password hashing (bcrypt)

📬 Email verification implemented using GCP Pub/Sub

🧪 Unit testing with Jest for backend APIs

🛠 Infrastructure provisioned using Terraform (networking, compute, SQL)

📦 Packer used to build VM images with automated setup scripts

🔁 GitHub Actions for CI/CD — automatic deployment on push

🌐 Configured DNS A record for custom domain

📈 Auto-scaling and load balancing for reliability and performance

⚙️ Deployment Architecture
Terraform provisions:

VPC, subnets, firewall rules

GCE VM Instance Template

Managed Instance Group

Cloud SQL instance

Pub/Sub for messaging

GitHub Actions pipeline:

Runs tests

Builds custom image via Packer

Deploys updated template to instance group

🔗 Links
- 📂 GitHub Repo: [Cloud_Craft](https://github.com/poojapk0605/Cloud_Craft)  
- 🔗 [LinkedIn Project](https://www.linkedin.com/in/poojakannanpk/)

📄 License
MIT License © 2025 Pooja Kannan
