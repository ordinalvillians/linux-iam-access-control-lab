# Linux IAM Access Control Lab

## 1. Project Overview

This project demonstrates basic Identity and Access Management (IAM) using Linux users, groups, directory ownership, and permissions in a Kali Linux virtual machine.

The objective is to apply the principle of least privilege by allowing users to access only the departmental resources required for their roles.

## 2. Lab Environment

- Operating System: Kali Linux
- Environment: VMware Workstation
- Access Control Method: Linux groups and file permissions

## 3. Users and Department Groups

| User | Department Group |
|------|------------------|
| Alice | IT |
| David | IT |
| Sarah | HR |
| John | Finance |

## 4. Access Control Configuration

Department directories were created for IT, HR, and Finance.

Each directory was assigned to its corresponding department group.

Permissions were configured using `chmod 770`, allowing the directory owner and members of the assigned group to access the directory while denying access to other users.

## 5. Access Testing

The following tests should be performed and recorded:

| Test | Expected Result | Actual Result |
|------|-----------------|---------------|
| Alice accesses IT directory | Allowed | Pending verification |
| Alice accesses Finance directory | Denied | Pending verification |
| Sarah accesses HR directory | Allowed | Pending verification |
| Sarah accesses IT directory | Denied | Pending verification |
| John accesses Finance directory | Allowed | Pending verification |
| John accesses HR directory | Denied | Pending verification |

## 6. Evidence

Screenshots will be added to the `screenshots` folder to demonstrate user and group configuration, directory permissions, successful access, and denied access.

## 7. Security Findings

Group-based permissions provide a simple way to separate departmental resources and limit unnecessary access.

The principle of least privilege reduces the risk of users accessing files outside their responsibilities.

## 8. Conclusion

This lab demonstrates how Linux user accounts, groups, ownership, and directory permissions can support basic access control.

Final results will be confirmed after the access tests are completed and the evidence has been reviewed.
