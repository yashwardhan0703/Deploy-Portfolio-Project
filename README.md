# 🚀 Automated Deployment of a DevOps Portfolio Website using GitHub Actions

This project demonstrates a **real-world CI/CD process** by deploying the **[tws-portfolio](https://github.com/LondheShubham153/tws-portfolio)** template using **GitHub Actions**.  
It simulates a scenario where a DevOps engineer takes an existing website source code and sets up an automated pipeline for **building** and **deploying** the site.

---

## 📌 Project Overview
- **Template Used:** [LondheShubham153/tws-portfolio](https://github.com/LondheShubham153/tws-portfolio)
- **Objective:** Showcase CI/CD skills by automating the deployment of a portfolio website.
- **Deployment Target:** GitHub Pages (can also be adapted for AWS S3, Netlify, or other hosting).
- **Tech Stack:**
  - HTML / CSS / JavaScript (Static site)
  - GitHub Actions (CI/CD)
  - YAML (Workflow configuration)
  - AWS S3 (optional bucket deployment policy included)

---

## 🛠 Features
- **Automated Deployment:** Any push to `main` triggers the pipeline to build and deploy the portfolio.
- **Version Control:** Each deployment is tied to a specific Git commit for easy rollback.
- **Reusable Workflow:** Can be adapted for any static or frontend project.
- **AWS Ready:** Includes an example **S3 bucket policy** file for cloud hosting.

---

## ⚙️ CI/CD Workflow

**Trigger:**  
- Push to `main` branch

**Pipeline Steps:**
1. **Checkout Code** – Clones the repository.
2. **Setup Node.js** – Configures environment for build tools.
3. **Install Dependencies** – Installs required packages.
4. **Build Project** – Generates production-ready output.
5. **Deploy to GitHub Pages** – Publishes automatically.

---

## 📂 Repository Structure
```plaintext
.
├── index.html                        # Main HTML file
├── README.md                         # Project documentation
│
├── .github/
│   └── workflows/
│       └── main.yml                   # GitHub Actions workflow
│
├── assets/
│   ├── favicon.ico
│   └── img/
│       ├── avataaars.svg
│       └── portfolio/
│           ├── cabin.png
│           ├── cake.png
│           ├── circus.png
│           ├── game.png
│           ├── safe.png
│           └── submarine.png
│
├── AWS - s3 bucket policy/
│   └── s3_bucket_policy.json          # AWS S3 bucket policy file
│
├── css/
│   └── styles.css                     # Stylesheet
│
└── js/
    └── scripts.js                     # JavaScript functionality
```

---
🌐 Live Demo

🔗 Deployed Site: http://portfolio-deployment-project.s3-website-us-east-1.amazonaws.com

---

📸 Screenshots

GitHub Actions Pipeline Run:


Deployed Portfolio Website:

---

🧠 Learning Outcomes

- Implemented GitHub Actions for automated builds and deployments.

- Learned how to adapt an existing project for CI/CD.

- Practiced working with workflow YAML configurations.

- Understood the end-to-end static site deployment process.

- Explored AWS S3 policy configuration for cloud deployments.

---

🙌 Acknowledgements

- GitHub Actions Documentation

- peaceiris/actions-gh-pages

- Original template author: Shubham Londhe
