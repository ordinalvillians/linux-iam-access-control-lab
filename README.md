# Linux IAM Access Control Lab

A hands-on Identity and Access Management (IAM) lab built in Kali Linux to demonstrate Linux user management, group-based access control, file permissions, and the principle of least privilege.

## Project Overview

This project simulates a small company with three departments:

- IT
- HR
- Finance

Each department has its own protected directory.

Users are assigned to department groups and are only permitted to access resources belonging to their assigned department.

The lab demonstrates how Linux groups, ownership, and permissions can be used to enforce basic access control.

## Objectives

- Create and manage Linux user accounts
- Create department-based security groups
- Assign users to appropriate groups
- Create protected departmental directories
- Configure ownership and permissions
- Test authorized access
- Test unauthorized access
- Document security findings with technical evidence

## Lab Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Virtualization | VMware Workstation |
| Access Control | Linux users and groups |
| Permission Model | Linux file and directory permissions |
| Repository | GitHub |

## IAM Structure

### Users

| User | Department | Group |
|---|---|---|
| Alice | IT | IT |
| David | IT | IT |
| Sarah | HR | HR |
| John | Finance | Finance |

### Department Resources

```text
/company/
├── IT/
├── HR/
└── Finance/
