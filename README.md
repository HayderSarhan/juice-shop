# Juice-Shop DevSecOps Project

## Overview

This project is focused on integrating **DevSecOps** practices into the development lifecycle of a deliberately vulnerable web application, **Juice-Shop**. Our aim is to automate security testing and vulnerability management in a **CI/CD pipeline** using modern security tools and best practices.

## Goal of the Project

The goal of this project is to demonstrate the implementation of **DevSecOps** by integrating **vulnerability scanning tools** into a **CI/CD pipeline** and using a **vulnerability management platform** to track and manage discovered vulnerabilities. We used the **Juice-Shop** app as a vulnerable test application to showcase this workflow.

### Tasks Accomplished:
1. **Vulnerability Scanning**: Integrated automated scanning tools (**CodeQL** and **njsscan**) to identify vulnerabilities in the application.
2. **CI/CD Pipeline Setup**: Configured **GitHub Actions** for continuous security testing, running scans on every commit and pull request.
3. **Vulnerability Management**: Deployed **DefectDojo**, an open-source vulnerability management platform, to track and visualize security findings from the scans.
4. **Reporting and Remediation**: Exported security scan results as **SARIF files** and imported them into DefectDojo for easy tracking and remediation planning.

## Tools Used

- [**Juice-Shop**](https://github.com/juice-shop/juice-shop): A deliberately vulnerable web application for testing and learning about security vulnerabilities. 
- **CodeQL**: A tool for static code analysis that helps identify vulnerabilities in the codebase.
- **njsscan**: A static analysis tool for identifying security vulnerabilities in JavaScript code.
- **GitHub Actions**: Used for automating the CI/CD pipeline and running security scans on every code update.
- [**DefectDojo**](https://github.com/DefectDojo/django-DefectDojo): An open-source vulnerability management platform to organize, prioritize, and track vulnerabilities across the project.


## Conclusion

This project demonstrates how to automate security testing and vulnerability management in modern software development. By integrating DevSecOps practices, we ensure that security is a continuous part of the development process and is tracked and managed in a central platform.