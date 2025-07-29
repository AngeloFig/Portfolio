# 👤 Identity & Access Management Labs

This section showcases hands-on labs focused on managing user identities, groups, and authentication policies in both Windows (Active Directory) and Linux environments. These skills are essential for cybersecurity, system administration, and IT support roles.

Whether you're building a secure domain environment or controlling user access across multiple systems, these labs reflect best practices in identity and access management.

---

## 🧱 Active Directory & Group Policy

- **Created Organizational Units (OUs)** to structure users and computers logically  
  ![Create OU](./ad-create-ou.png)

- **Added Users to the Domain** and configured account properties  
  ![Create User](./ad-create-user.png)  
  ![User Password Settings](./ad-create-user2.png)

- **Created Security Groups** and managed user memberships  
  ![Create Group](./ad-create-group.png)

- **Linked Group Policy Objects (GPOs)** to specific OUs for centralized control  
  ![Link GPO](./ad-link-gpo.png)

---

## 🪪 Windows Account Security

- **Configured password complexity and lockout settings** via policy editor  
  ![Password Policy](./win-password-policy.png)

- **Restricted local accounts** to reduce unauthorized access points  
  ![Restrict Local Accounts](./win-restrict-local-accounts.png)

- **Enforced User Account Control (UAC)** for elevation prompts and privilege management  
  ![UAC Settings](./win-uac-settings.png)

- **Implemented Smart Card Authentication** for multifactor login (where supported)  
  ![Smart Card Auth](./win-smart-card-auth.png)

---

## 🐧 Linux User & Group Management

- **Created, renamed, and deleted users** with CLI tools like `useradd`, `usermod`, and `userdel`  
  ![Add User](./linux-user-management-useradd.png)  
  ![Delete User](./linux-user-management-userdel.png)  
  ![Rename User](./linux-user-management-usermod.png)

- **Changed passwords and locked accounts** using `passwd` and `usermod -L`  
  ![Change Password](./linux-password-management-passwd.png)  
  ![Lock Account](./linux-password-management-lock.png)

- **Created and managed groups** and added users to the correct security groups  
  ![Group Management](./linux-group-management.png)

---

> ✅ These foundational IAM skills are crucial whether I’m working toward a cybersecurity analyst role or starting in help desk/system support. They ensure secure and organized access across enterprise systems.

