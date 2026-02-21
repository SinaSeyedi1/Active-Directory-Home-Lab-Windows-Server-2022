# File Share and Permissions Configuration

This section demonstrates the configuration of shared folders and access control using NTFS permissions and Security Groups in Windows Server 2022.

This simulates common Helpdesk scenarios such as granting access to shared drives, troubleshooting "Access Denied" errors, and managing permission-based access.

---

## Objectives

- Create shared folder on Domain Controller
- Configure Share Permissions
- Configure NTFS Permissions
- Assign Security Group access to shared folder
- Test access control using group membership
- Simulate access revocation

---

## Actions Performed

- Created shared folder: \\DC01\FileShare
- Configured Share Permissions to allow Security Group access
- Assigned NTFS permissions to SG-FileShare-Users
- Verified that LabUser2 could access the shared folder
- Removed user from group to simulate access removal
- Confirmed access denial after removal

This setup demonstrates understanding of layered permission models (Share + NTFS) and group-based access control used in enterprise environments.

---

## Skills Demonstrated

- Windows File Share configuration
- NTFS permission management
- Security group-based access control
- Access troubleshooting methodology
- Principle of Least Privilege
