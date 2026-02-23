User Onboarding Process
Overview

This section demonstrates a structured user onboarding process in Active Directory using Windows Server 2022. The goal is to simulate how a helpdesk or junior system administrator would provision access for a new employee in a corporate environment.

Scenario

A new employee joins the organisation and requires:

A domain user account

Placement in the correct Organizational Unit (OU)

Membership in appropriate security groups

Access to shared resources

Steps Performed
1. User Account Creation

Created a new domain user in the Corp-Users OU.

Configured initial password settings.

Enabled "User must change password at next logon".

Screenshot:
01-users-created-in-corp-users.png

2. Security Group Assignment

Created or identified the required security group.

Added the user to the relevant security group to grant access.

Screenshot:
02-security-group-created.png
03-user-added-to-security-group.png

Outcome

The user account was successfully provisioned with:

Proper OU placement

Correct security group membership

Controlled access to shared resources

This demonstrates structured onboarding aligned with common enterprise Active Directory practices.
