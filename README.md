# Technical Documentation (Secure DevOps Pipeline for Kubernetes Deployment)

## Overview

![Flow Diagram](https://res.cloudinary.com/dnw22sl1p/image/upload/v1731708239/Distributed%20Search%20Engine/secureDevOpsPipe_asg9gk.png)

**Description**: This Agile-driven project automated the CI/CD pipeline for deploying a Spring Boot application on a Kubernetes cluster. Using Jenkins, the pipeline streamlined code compilation, testing, static analysis with SonarQube, and vulnerability scanning via OWASP Dependency-Check. Maven-built artifacts were stored in Nexus, while Docker packaged the application and dependencies, with Aqua Trivy ensuring container security before pushing images to Docker Hub. Jenkins deployed the application to the Kubernetes cluster using `kubectl`.

**Purpose**: To build a secure deployment pipeline that ensures business continuity and maintains high code quality.

## Technology Stack
**Languages**: Java, Bash

**Tools**: Git, Jenkins, Docker, Kubernetes, Spring, Maven, VMware
## Infrastructure Setup
### Kubernetes Cluster Setup
#### Control Plane Nodes (Master Nodes)
3 control plane nodes each with the below computing resources specifications:
- **CPU**: 2 vCPUs per node
- **Memory**: 4 GB RAM per node
- **Disk**: 50 GB ROM for the operating system and Kubernetes components
- **Operating System**: Linux Ubuntu 20.04 LTS
- **Networking**: Network connectivity between control plane nodes

#### Worker Nodes
2 worker nodes each with the below computing resources specifications:
- **CPU**: 2 vCPUs per node
- **Memory**: 4 GB RAM per node
- **Disk**: 30 GB ROM for the operating system and Kubernetes components
- **Operating System**: Linux Ubuntu 20.04 LTS
- **Networking**: Network connectivity between control plane and worker nodes
## CI/CD Pipeline
## Configuration Management
