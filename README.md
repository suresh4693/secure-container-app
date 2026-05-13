# Secure Container DevSecOps Pipeline

This project automates security scanning for a containerized application using:

- AWS CodePipeline
- AWS CodeBuild
- Docker
- Amazon ECR
- Trivy

## Features

- Automated Docker builds
- Vulnerability scanning
- CI/CD pipeline
- Secure image deployment

## Security

Trivy scans images for:

- HIGH vulnerabilities
- CRITICAL vulnerabilities

The pipeline automatically fails if vulnerabilities are detected.