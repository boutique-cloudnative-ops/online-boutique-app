# Online Boutique - Microservices Demo (AWS Edition)

This is a modified version of the Google Online Boutique, optimized for **AWS Infrastructure** and **GitOps** workflows.

## 🚀 Project Overview

- **Application:** 11 Polyglot Microservices (Go, Python, Node.js, Java, etc.)
- **Platform:** AWS (EC2, ECR, S3)
- **Kubernetes:** K3s
- **CI/CD:** GitHub Actions & ArgoCD

## 🛠 Project Structure

This repository focuses solely on the **Source Code** and **CI Pipelines**.

- `/src`: Contains the source code for each microservice.
- `/pb`: Protocol Buffer definitions for gRPC.
- `.github/workflows`: CI pipelines for building and pushing images to Amazon ECR.

## 🔗 Related Repositories

- 🏠 [Main Portal & Architecture](link_den_repo_portal)
- 🏗 [Infrastructure as Code (Terraform & Ansible)](link_den_repo_iac)
- ⚓ [GitOps Manifests & Helm Charts](link_den_repo_gitops)

---

_Note: This project is based on the [Google Cloud Microservices Demo](https://github.com/GoogleCloudPlatform/microservices-demo)._
