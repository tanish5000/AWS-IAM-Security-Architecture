# Enterprise AWS IAM Security Architecture

## Project Overview

This project demonstrates the implementation of a secure AWS Identity and Access Management (IAM) environment following enterprise security best practices.

The architecture implements:

- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Multi-Factor Authentication (MFA)
- Custom IAM Policies
- IAM Policy Simulator Validation
- IAM Access Analyzer
- AWS Credential Report

The project simulates a real organization by creating different departments with separate permissions and validating that users only have the access required for their job roles.

---

# Objectives

- Create a secure AWS IAM environment
- Implement Role-Based Access Control (RBAC)
- Enforce Least Privilege access
- Configure Multi-Factor Authentication (MFA)
- Create custom IAM JSON policies
- Validate permissions using IAM Policy Simulator
- Monitor security using Access Analyzer
- Audit identities using Credential Report

---

# Architecture

```
                    AWS Account
                         │
                    Root Account
                    MFA Enabled
                         │
        ┌────────────────┼─────────────────┐
        │                │                 │
 SecurityAdmins      Developers        Finance
        │                │                 │
  Khera-admin      garv-devops      Pratyush-finance
        │                │                 │
 Administrator   Least Privilege   Billing Read Only
```

---

# Security Controls

- Role-Based Access Control (RBAC)
- Least Privilege Access
- Explicit Deny Policy
- Multi-Factor Authentication
- IAM Password Policy
- IAM Policy Simulator
- IAM Access Analyzer
- Credential Report

---

# Technologies Used

- Amazon Web Services (AWS)
- AWS IAM
- IAM Policy Simulator
- IAM Access Analyzer
- AWS Credential Report
- JSON
- GitHub

---

# Project Structure

```
AWS-IAM-Security-Architecture/
│
├── architecture/
├── diagrams/
├── policies/
├── reports/
├── screenshots/
└── README.md
```

---

# Validation Performed

✅ Developer can view EC2 resources.

✅ Developer cannot create IAM users.

✅ Explicit Deny policy overrides Allow.

✅ Access Analyzer configured.

✅ Credential Report generated.

---

# Screenshots

The repository contains screenshots demonstrating:

- IAM Users
- IAM Groups
- Custom Policies
- MFA Configuration
- Policy Simulator
- Access Analyzer
- Credential Report

---

## Repository Structure

```
AWS-IAM-Security-Architecture
│
├── policies
├── reports
├── architecture
├── Screenshots
├── LICENSE
├── README.md
└── .gitignore
```

## Skills Demonstrated

- AWS IAM
- Identity and Access Management
- Least Privilege
- Role Based Access Control
- Multi-Factor Authentication
- IAM Policy Simulator
- Access Analyzer
- Credential Report
- AWS Security Best Practices

# Author

**Tanish Khera**

Cybersecurity | Cloud Security | AWS IAM
