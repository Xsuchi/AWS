![alt text](img/1_b6PXkHPT7LVETzLwrVQCUw.png)

# AWS IAM – Identity & Access Management (Scenario-Based Hands-On)

This repository contains **real-world IAM scenarios** that mirror how access, security, and identity are managed in production AWS environments.

---

##  **Scenarios Covered**

### **Scenario 1 – IAM Users, Groups, Policies, and Permissions**
Creating users, assigning them to groups, and attaching least-privilege policies.

---

### **Scenario 2 – Enforcing MFA for Users**
Adding MFA (Multi-Factor Authentication) to secure IAM identities.

---

### **Scenario 3: if you need to change the password complexity or password expiration.** 
Changing password complexity, rotation rules, expiration, and account security settings.

---

### **Scenario 4: As per the security audit you want a list of users and their status of when was password changed?Do they have MFA? When they last used this password? [ credential report]**
Generating a credential report to analyze:
- Last password change  
- MFA enablement  
- Last access activity  
- Access key usage  

---

### **Scenario 5 – Identify Unused Permissions [Access Advisor]**
Using Access Advisor to remove permissions that are not used by the user (S3, EC2, etc).

---

### **Scenario 6: There is a user who is fascinated using aws via CLI. He is bored of login into console and navigating. [access keys CLI]**
Configuring access keys for users who want to use AWS CLI instead of console login.

---

### **Scenario 7: Instead of installing any applications can user access AWS via CLI?? [cloudshell]**
Using CloudShell to run AWS CLI commands without installing anything locally.

---

Each scenario includes:
- Problem statement  
- Step-by-step solution  
- Screenshot evidence  
- Relevant AWS policies  
- Commands used  
