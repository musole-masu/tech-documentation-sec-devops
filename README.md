# Technical Documentation (Secure DevOps Pipeline for Kubernetes Deployment)

## Overview

![Flow Diagram](https://res.cloudinary.com/dnw22sl1p/image/upload/v1731708239/Distributed%20Search%20Engine/secureDevOpsPipe_asg9gk.png)

**Description**: This Agile-driven project automated the CI/CD pipeline for deploying a Spring Boot application on a Kubernetes cluster. Using Jenkins, the pipeline streamlined code compilation, testing, static analysis with SonarQube, and vulnerability scanning via OWASP Dependency-Check. Maven-built artifacts were stored in Nexus, while Docker packaged the application and dependencies, with Aqua Trivy ensuring container security before pushing images to Docker Hub. Jenkins deployed the application to the Kubernetes cluster using `kubectl`.

**Purpose**: To build a secure deployment pipeline that ensures business continuity and maintains high code quality.
