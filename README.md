# Active Directory Home Lab – Windows Server 2022

## Overview

This project demonstrates the deployment and configuration of a Windows Server 2022 Active Directory Domain Controller in a virtual lab environment.

The lab simulates real-world IT Support tasks including user management, security group configuration, file share permissions, Group Policy enforcement, and password troubleshooting.

---

## Environment

- Windows Server 2022 Standard (Evaluation)
- Active Directory Domain Services (AD DS)
- Group Policy Management
- VirtualBox
- Command Prompt (CLI validation)

---

## Key Configurations Performed

### Domain Controller Deployment
- Renamed server to DC01
- Created new forest (sinaseyedi.local)
- Configured DNS and Global Catalog
- Promoted server to Domain Controller

### User and Access Management
- Created structured OUs (Corp-Users, Security-Groups)
- Provisioned domain users
- Implemented role-based access using security groups

### File Share & Permissions
- Created shared folder (CorpData)
- Configured NTFS permissions
- Configured Share permissions
- Applied principle of least privilege

### Group Policy Configuration
- Configured password policy
- Configured account lockout policy
- Validated policies using Group Policy Modeling

### Troubleshooting & Validation
- Forced password change at next logon
- Tested authentication behavior using `runas`
- Verified user attributes using `net user /domain`

---

## Skills Demonstrated

- Active Directory administration
- User provisioning and lifecycle management
- Security group-based access control
- NTFS vs Share permission troubleshooting
- Group Policy configuration and validation
- Account lockout troubleshooting
- Command-line verification techniques
- Real-world helpdesk scenario simulation
