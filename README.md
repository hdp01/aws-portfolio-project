# 🌐 Static Portfolio Hosting on AWS using Terraform & GitHub Actions

Deploy your static portfolio website using **AWS S3**, **CloudFront**, **Terraform**, and **GitHub Actions** for CI/CD.

---

## 🛠️ Tech Stack

- AWS S3 & CloudFront
- Terraform (IaC)
- GitHub Actions (CI/CD)
- IAM (for AWS credentials)

---

## 📁 Project Structure

```
aws-portfolio-project/
├── public/                # Static site files
├── terraform/             # Terraform configs
├── docs/                  # Documentation files
└── .github/workflows/     # GitHub Actions pipeline
```

---

## 🚀 Live Demo

> **No live demo available currently.**  
All AWS resources have been removed to avoid ongoing costs.

---

## ⚡ Quick Start

1. **Clone this repository.**
2. **Set up AWS credentials** with an IAM user and required permissions.
3. **Provision AWS infrastructure** using the Terraform files.
4. **Upload your static site files** to the S3 bucket.
5. **Configure GitHub Actions** with your AWS secrets for automatic deployment.

For detailed instructions, see the [documentation (PDF)](./docs/AWS_Portfolio_Project_Documentation.pdf).

---

## 🧹 Teardown

- Remove files from your S3 bucket.
- Destroy the resources using Terraform.
- Optionally delete the IAM user.

---

## 📄 Documentation

For complete setup, configuration, and troubleshooting, please see the  
[**Static Portfolio Hosting on AWS using Terraform & GitHub Actions** (PDF)](./docs/AWS_Portfolio_Project_Documentation.pdf).

---

## 👤 Author

**Harsh Pashine**  
[LinkedIn](https://www.linkedin.com/in/harsh-pashine-434ab4223) | [GitHub](https://github.com/hdp01)
