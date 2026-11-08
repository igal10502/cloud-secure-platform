# cloud-secure-platform

A secure, production-style platform on AWS, built entirely with Infrastructure as Code, plus a Python tool that scans AWS accounts for security misconfigurations.

> 🚧 Work in progress: built over 12 weeks. Progress is tracked below.

## What's inside

| Folder | What it is |
| --- | --- |
| [`app/`](app/) | Python REST API (FastAPI + PostgreSQL), packaged with Docker |
| [`infra/`](infra/) | Terraform for AWS: VPC, ECS Fargate, ALB with HTTPS, RDS, IAM |
| [`scanner/`](scanner/) | Python/boto3 tool that finds AWS security misconfigurations |
| [`.github/workflows/`](.github/workflows/) | CI/CD: tests, deploys via OIDC, scheduled security scans |
| [`docs/`](docs/) | Architecture diagrams and screenshots |

## Tech stack

Python · FastAPI · PostgreSQL · Docker · Terraform · AWS (VPC, ECS Fargate, ECR, ALB, RDS, Secrets Manager, CloudWatch, IAM) · GitHub Actions · boto3

## Progress

- [ ] Week 1: AWS account, IAM, app running locally with Docker Compose
- [ ] Week 2: Terraform basics and remote state
- [ ] Week 3: VPC networking
- [ ] Week 4: ECR and ECS Fargate
- [ ] Week 5: Load balancer, HTTPS, RDS
- [ ] Week 6: Secrets, least-privilege IAM, security groups
- [ ] Week 7: CI/CD with GitHub Actions and OIDC
- [ ] Week 8: Auto-scaling, monitoring, load testing
- [ ] Week 9–11: Security scanner
- [ ] Week 12: Final docs and demo
