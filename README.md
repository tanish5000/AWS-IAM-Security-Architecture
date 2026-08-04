---

# Architecture Overview

The AWS account was configured using Role-Based Access Control (RBAC) to ensure that permissions were assigned according to business responsibilities rather than individual users.

The environment consists of three IAM groups representing different organizational departments:

- **SecurityAdmins**
- **Developers**
- **Finance**

Each user inherits permissions through group membership instead of direct policy assignments. This approach improves scalability, simplifies permission management, and follows enterprise IAM best practices.

## IAM Architecture

```text
                     AWS Account
                          │
                     Root Account
                     MFA Enabled
                          │
        ┌─────────────────┼─────────────────┐
        │                 │                 │
 SecurityAdmins      Developers        Finance
        │                 │                 │
  khera-admin       garav-devops     pratyush-finance
        │                 │                 │
 Administrator     Least Privilege   Billing Read Only
```

---

# Security Controls Implemented

The following security controls were implemented during the project:

- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Multi-Factor Authentication (MFA)
- Custom IAM Policies
- Explicit Deny Policy
- IAM Policy Simulator Validation
- IAM Access Analyzer
- Credential Report Auditing
- Strong IAM Password Policy

---
