# User Offboarding Process

## Overview

This section demonstrates secure user deprovisioning in Active Directory.

---

## Scenario

A user is leaving the organisation and must have all access revoked.

---

## Step 1 – Create Disabled Users OU

A Disabled-Users OU was created to store inactive accounts.

![Disabled Users OU](01-User-Offboarding.png)

---

## Step 2 – Remove From Security Groups

The user was removed from assigned security groups to revoke access.

![Removed From Security Group](02-User-Account-Disabled.png)

---

## Step 3 – Disable User Account

The account was disabled to prevent authentication.

![User Disabled](03-Removed-From-Security-Group.png)

---

## Step 4 – Verify Account Status

Verification was performed using:

net user "Lab User 2" /domain

The output confirmed Account active: No.

![Verification](04-Account-Disabled-Verification-Net-User.png)

---

## Step 5 – Move User to Disabled OU

The account was moved to the Disabled-Users OU for directory hygiene.

![Moved to Disabled OU](05-User-Moved-To-Disabled-Users-OU.png)

---

## Outcome

The account was securely deprovisioned using structured offboarding practices including access removal, account disabling, and verification.
