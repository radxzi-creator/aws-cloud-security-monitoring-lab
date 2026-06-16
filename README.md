<img width="1536" height="1024" alt="AWS CLOUD SEC MONITORING ARCHITECTURE" src="https://github.com/user-attachments/assets/38834af1-bca3-4fd3-af4c-b50a2b60999b" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152743" src="https://github.com/user-attachments/assets/889f6222-347a-4d2b-b819-08ec1de41239" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152723" src="https://github.com/user-attachments/assets/7c98ef4e-0623-4930-b4ec-7c15fbe222b5" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152608" src="https://github.com/user-attachments/assets/dff9c39e-b788-4908-8a5c-3469c137a360" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152538" src="https://github.com/user-attachments/assets/8a7fa5c4-ac73-4b04-b1a4-fe729c0a578f" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152523" src="https://github.com/user-attachments/assets/a00de144-9fcc-44a6-b565-e130f9914894" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152406" src="https://github.com/user-attachments/assets/1fb3f937-1041-4263-b38a-e328beaddc50" />
<img width="1522" height="1140" alt="Screenshot 2026-06-16 152926 1" src="https://github.com/user-attachments/assets/5f08f788-9313-4420-9bff-731d02c8143d" />
AWS Cloud Security Monitoring Lab

Overview

This project demonstrates a cloud security monitoring system built on AWS that detects IAM activity and triggers real-time alerts using an event-driven architecture.

Architecture

IAM → CloudTrail → CloudWatch Logs → Metric Filter → CloudWatch Alarm → SNS Email Notification

AWS Services Used

AWS IAM (Identity and Access Management)
AWS CloudTrail (Audit logging)
Amazon CloudWatch (Metrics, Logs, Alarms)
Amazon SNS (Email notifications)

Security Detection

The system detects IAM events such as:

User creation
Role changes
Policy modifications

When a security event occurs, an automated alert is triggered via email in near real-time.

What I Learned

Cloud security monitoring fundamentals
IAM event tracking and auditing
CloudWatch metric filters and alarms
Event-driven security architecture in AWS
SOC-style alerting workflows

