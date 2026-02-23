User Offboarding Process
Overview

This section demonstrates a structured user offboarding process in Active Directory using Windows Server 2022. The objective is to securely deprovision a departing user by removing access, disabling the account, and maintaining directory hygiene.

This simulates how a helpdesk or junior system administrator would handle user lifecycle management in a corporate environment.

Scenario

A user is leaving the organisation and must no longer have access to domain resources.

The following steps were performed to ensure secure and controlled deprovisioning.

Step 1 – Create Disabled Users OU

A dedicated Disabled-Users Organizational Unit was created to store inactive accounts.
This helps maintain a clean and organised Active Directory structure.

Screenshot:
00-Disabled-Users-OU-Created.png

Step 2 – Remove From Security Groups

The user was removed from assigned security groups to immediately revoke access to shared resources.

Screenshot:
01-Removed-From-Security-Group.png

Step 3 – Disable User Account

The account was disabled to prevent any further authentication attempts.

Screenshot:
02-User-Account-Disabled.png

Step 4 – Move Account to Disabled OU

The user account was moved to the Disabled-Users OU to separate inactive accounts from active users.

Screenshot:
03-User-Moved-To-Disabled-Users-OU.png

Step 5 – Verify Account Status

Account status was verified using the command:

net user "Lab User 2" /domain

Verification confirmed:

Account active: No

Screenshot:
04-Account-Disabled-Verification-Net-User.png

Outcome

The user account was successfully deprovisioned following structured enterprise practices:

Access revoked

Account disabled

Directory organised

Status verified

This demonstrates practical understanding of secure user lifecycle management in Active Directory.
