# Azure IAM Security Lab

## Overview

My project demonstrates identity and access management (IAM) concepts within Microsoft Azure using Microsoft Entra ID. The lab focuses on user administration, group management, role-based access control (RBAC), and multi-factor authentication (MFA) to simulate how organizations secure access to cloud resources.

## Objectives

- Create and manage users in Microsoft Entra ID
- Create security groups and assign users
- Implement Role-Based Access Control (RBAC)
- Apply least-privilege access principles
- Configure Multi-Factor Authentication (MFA)
- Research Conditional Access policies and licensing requirements

## Environment

- Microsoft Azure
- Microsoft Entra ID
- Azure Resource Groups
- Azure RBAC

## Architecture

Users
↓
Groups
↓
RBAC Roles
↓
Azure Resources

## Users Created

- Sarah HR
- Mike Finance
- Tom IT
- Emma Security
- Jack Intern

## Groups Created

- HR-Team
- Finance-Team
- IT-Team
- Security-Team

## RBAC Assignments

| User | Role |
|--------|--------|
| Tom IT | Contributor |
| Emma Security | User Access Adminstrator |
| Sarah HR | Reader |

## Security Concepts Demonstrated

### Least Privilege
Least privilege is a security principle that grants users only the permissions necessary to perform their job responsibilities. In this project, I created different Azure roles that were assigned based on user responsibilities only to minimize unnecessary access and reduce security risk.

### Role-Based Access Control (RBAC)
Role-Based Access Control (RBAC) is an authorization model that assigns permissions through predefined roles rather than directly to users. In this lab, Reader, Contributor, and User Access Administrator roles were chosen and used to demonstrate how organizations control access to Azure resources while maintaining security and accountability.

### Multi-Factor Authentication (MFA)
Multi-Factor Authentication (MFA) strengthens account security by requiring multiple forms of verification before granting access. MFA helps protect against compromised passwords and unauthorized access attempts by adding an additional layer of authentication.

### Conditional Access
Conditional Access is a Microsoft Entra ID security feature that allows organizations to enforce access policies based on user, device, location, risk level, and other conditions. Although I was not able to configure Conditional Access due to Microsoft Entra ID Premium licensing requirements, its functionality was researched and documented as part of this project.

## Key Skills Demonstrated

- Microsoft Azure
- Microsoft Entra ID
- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Cloud Security Fundamentals

## Project Screenshots

### Users
![Users](screenshots/users.png)

### Groups
![Groups](screenshots/groups.png)

### Resource Group
![Resource Group](screenshots/resource-group.png)

### RBAC Assignments
![RBAC](screenshots/rbac.png)

### MFA Configuration
![MFA](screenshots/mfa.png)

### Conditional Access Licensing Requirement
![Conditional Access](screenshots/conditional-access.png)
