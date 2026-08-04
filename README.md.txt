# Enterprise AWS IAM Security Architecture

## Project Overview

This project demonstrates the design and implementation of a secure Identity and Access Management (IAM) architecture in Amazon Web Services (AWS). The environment was built following security best practices including Role-Based Access Control (RBAC), the Principle of Least Privilege, Multi-Factor Authentication (MFA), IAM policy validation, and identity governance.

The project simulates an enterprise environment by creating dedicated IAM groups and users for Security, Development, and Finance teams. Custom IAM policies were implemented to restrict access based on job responsibilities while preventing privilege escalation through explicit deny policies.

The security configuration was validated using the AWS IAM Policy Simulator, IAM Access Analyzer, and Credential Report to ensure that permissions were correctly enforced and that no unintended external access existed.

---

## Objectives

- Design a secure AWS IAM architecture.
- Implement Role-Based Access Control (RBAC).
- Apply the Principle of Least Privilege.
- Enforce Multi-Factor Authentication (MFA).
- Create and attach custom JSON IAM policies.
- Validate permissions using AWS IAM Policy Simulator.
- Monitor resource exposure using IAM Access Analyzer.
- Audit IAM identities using AWS Credential Report.
- Document the implementation following enterprise security practices.

---

## Technologies Used

- Amazon Web Services (AWS)
- AWS Identity and Access Management (IAM)
- IAM Policy Simulator
- IAM Access Analyzer
- AWS Credential Report
- JSON
- GitHub