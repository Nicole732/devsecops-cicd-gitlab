# 🔐 Full DevSecOps CI/CD Pipeline with GitLab

A demonstration of a fully automated DevSecOps pipeline built with GitLab CI/CD, integrating security testing at every stage of the software delivery lifecycle. This project showcases how to shift security left by embedding SAST, DAST, and SCA directly into the pipeline.


## 📋 Table of Contents

- [Overview](#overview)
- [Pipeline Architecture](#pipeline-architecture)
- [Stages](#stages)
- [Security Tools](#security-tools)
- [Setup & Configuration](#setup--configuration)
- [Pipeline Configuration](#pipeline-configuration)
- [Usage](#usage)
- [Contributing](#contributing)


## Overview

This project demonstrates a production-style DevSecOps pipeline that automatically:

- Builds and installs application dependencies
- Runs unit and lint tests
- Performs **SAST** (Static Application Security Testing) using Horusec
- Performs **DAST** (Dynamic Application Security Testing) using OWASP ZAP
- Performs **SCA** (Software Composition Analysis) using Snyk
- Deploys the application after all checks pass

Security gates are enforced at the pipeline level — **critical vulnerabilities block deployment**.

