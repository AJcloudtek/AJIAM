# Hi, I'm AJ!

## Identity and Access Management (IAM)

CompTIA Security+ Certified | Microsoft Azure Fundamentals | Microsoft Entra ID

Documenting my hands-on IAM projects involving cloud identity administration, user provisioning, role assignments, and access management.
## Microsoft Entra ID Projects

### 1. User Creation and Provisioning
Created and managed user accounts in Microsoft Entra ID as part of a hands-on IAM lab.
<img width="948" height="445" alt="IMG_9230" src="https://github.com/user-attachments/assets/58678ee1-42ba-4f66-a3c9-d184ff1df581" />

### 2. Cloud Provisioning and Licensing
Practiced cloud-based user provisioning and license assignments.
<img width="935" height="416" alt="IMG_9234" src="https://github.com/user-attachments/assets/4cea9cd7-2a3e-405c-b60d-a598fe54f6a9" />


### 3. Role Assignments (RBAC)
Assigned directory roles and explored role-based access control and least privilege.
<img width="949" height="438" alt="IMG_9237" src="https://github.com/user-attachments/assets/34c51c75-9064-4a62-a0cf-7c476c4d58b1" />


### 4. Group Assignments
Configured security groups and assigned users to groups to manage access.
<img width="952" height="446" alt="IMG_9239" src="https://github.com/user-attachments/assets/7e61e636-8144-44b1-81d0-81793a2ecbe5" />

### 5. Identity Lifecycle Management (Joiner–Mover–Leaver)

Practiced identity lifecycle management in Microsoft Entra ID, including user provisioning, changes to employee attributes, and offboarding.
### Joiner – User Onboarding

Created a new user in Microsoft Entra ID and configured initial access through user provisioning, group membership, and role assignments. 

![Joiner account overview](screenshots/Joiner%20account%20overview.png)

![Joiner group membership](screenshots/Joiner%20group%20membership.png)

![Joiner role assignment](screenshots/Joiner%20role%20assignment.png)

![Joiner license assignment](screenshots/Joiner%20license%20assignment.png)

### Mover – User Access Changes

Updated GWashington's job title and department to reflect a move to the Human Resources department. Reviewed HR group membership and documented the changes using Microsoft Entra ID audit logs.

**1. Updated Job Information**

![Mover HR job information](screenshots/Mover%20HR%20job%20info.png)

**2. HR Group Membership**

![Mover HR group membership](screenshots/Mover%20HR%20group%20membership.png)

**3. Job Change Audit Log**

![Mover job change audit log](screenshots/Move%20job%20change%20audit%20log.png)
#### Leaver – User Offboarding

Documented the offboarding process through account disabling, session revocation, group membership removal, license removal, role access review, and audit logs.

#### Offboarding Evidence

**1. Account Before Offboarding**

![Account enabled](screenshots/Leaver%20account%20enabled.png)

**2. Account Disabled**

![Account disabled](screenshots/Leaver%20account%20disabled.png)

**3. Session Revocation**

![Session revocation](screenshots/Leaver%20account%20revocation.png)

**4. Group Membership Removal**

![Group membership before](screenshots/Leaver%20groups%20membership%20before.png)

![Group removal](screenshots/Leaver%20group%20removal.png)

![Group membership after](screenshots/Leaver%20group%20after.png)

**5. License Removal**

![License before](screenshots/Leaver%20License%20before.png)

![License removed](screenshots/Leaver%20licensce%20removed.png)

![License removal audit log](screenshots/Leaver%20License%20removal%20audit%20log.png)

**6. Role Access Review**

![Role before](screenshots/Leaver%20role%20before.png)

![Role removal confirmation](screenshots/Leaver%20role%20after.png)
![Role after removal](screenshots/Leaver%20role%20after%202.png)
**7. Offboarding Audit Logs**

![Account audit logs](screenshots/Leaver%20audit%20logs.png)

![Offboarding audit logs](screenshots/leaver%20off%20boarding%20audit%20logs.png)
## 6. Authentication Methods Review

Reviewed authentication method options for a test user in Microsoft Entra ID.

Explored the available authentication methods, including email, phone numbers, and Temporary Access Pass. No changes were made to the user's authentication settings.

### Authentication Methods Screenshot

![Authentication Methods Review](screenshots/Authentication%20methods%20review.png)
## 7. Sign-In Logs Review

Reviewed Microsoft Entra ID sign-in logs to examine user sign-in activity and authentication results.

Examined a successful sign-in record showing a multifactor authentication (MFA) requirement. The authentication details indicated that the MFA requirement was satisfied by a claim in the token, with previously satisfied authentication steps.

This exercise demonstrated how to review sign-in activity and interpret authentication information for identity monitoring.
