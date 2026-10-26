# AWS-Root-Account-MFA-Hardening

AWS Cloud Security: Root Account MFA Hardening & Identity Assurance

📌 Project Overview

This project demonstrates how to strengthen AWS account security by enabling Multi-Factor Authentication (MFA) for the root user and following Identity and Access Management (IAM) security best practices.

🎯 Objectives

- Secure the AWS root account with MFA.
- Reduce unnecessary root account usage.
- Avoid creating access keys for the root user.
- Apply the principle of least privilege.
- Improve identity assurance and access control.
- Review and monitor account security.

🛠️ Services and Tools

- Amazon Web Services (AWS)
- AWS Identity and Access Management (IAM)
- AWS Management Console
- Virtual MFA Authenticator
- AWS CloudTrail (for access activity monitoring)

# Hardening & Deployment Methodology

Phase 1: Initial Root Access & Security Posture Assessment
Initiated the administrative session by navigating to the AWS Management Console Sign-In portal (signin.aws.amazon.com). Selected the Root user authentication option and supplied the account owner root email address.
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/a0cc4966-5d56-42fa-9ffe-e0112e6e484b" />
Supplied the root master password to satisfy the primary authentication factor.
<img width="1916" height="966" alt="image" src="https://github.com/user-attachments/assets/8eb79199-45f0-4aca-a839-985a56756f82" />

# Step1:-
Login the AWS Account With root user 
<img width="1920" height="970" alt="image" src="https://github.com/user-attachments/assets/35cba431-eefe-45e4-b8ba-d7fef43d6ecd" />

# Step2:-
Navigated to the global service locator and searched for IAM (Identity and Access Management) to audit security configurations.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/805f2ed5-8435-44db-95ad-ec004f8b7bee" />

Inspected the IAM Dashboard overview. The console reported an active security posture alert:

Recommendation: "Add MFA for root user - Enable multi-factor authentication (MFA) for the root user to improve security for this account."
Selected Add MFA to launch the device association wizard.



