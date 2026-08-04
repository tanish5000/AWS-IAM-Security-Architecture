# AWS IAM Security Risk Assessment

## Executive Summary

This project implements a secure AWS Identity and Access Management (IAM) architecture using enterprise security best practices. The primary objective was to reduce unauthorized access, enforce the Principle of Least Privilege, and improve identity governance through Role-Based Access Control (RBAC), Multi-Factor Authentication (MFA), custom IAM policies, and continuous security validation.

---

## Scope

The assessment covers:

- AWS IAM Users
- IAM Groups
- Custom IAM Policies
- Multi-Factor Authentication (MFA)
- IAM Policy Simulator
- IAM Access Analyzer
- AWS Credential Report

---

## Identified Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| Excessive user permissions | High | Implemented Least Privilege policies |
| Privilege escalation | High | Explicit Deny IAM policy |
| Password compromise | High | MFA enabled |
| Misconfigured permissions | Medium | Validated using IAM Policy Simulator |
| External resource exposure | Medium | IAM Access Analyzer configured |
| Weak identity governance | Medium | Credential Report generated for auditing |

---

## Security Controls Implemented

- Role-Based Access Control (RBAC)
- Principle of Least Privilege
- Multi-Factor Authentication
- Strong IAM Password Policy
- Custom JSON Policies
- Explicit Deny Policy
- IAM Policy Simulator Validation
- IAM Access Analyzer
- Credential Reporting

---

## Residual Risk

The implemented controls significantly reduce the likelihood of unauthorized access and privilege escalation. Residual risk remains low because administrative access is restricted, permissions are validated, and external resource exposure is continuously monitored.

---

## Conclusion

The AWS IAM environment demonstrates secure identity and access management practices suitable for small and medium enterprise environments. The implementation follows AWS security best practices by enforcing least privilege, validating permissions, enabling MFA, and monitoring account security through auditing and analysis tools.
