<img width="1536" height="1024" alt="AWS CLOUD SEC MONITORING ARCHITECTURE" src="https://github.com/user-attachments/assets/38834af1-bca3-4fd3-af4c-b50a2b60999b" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152743" src="https://github.com/user-attachments/assets/889f6222-347a-4d2b-b819-08ec1de41239" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152723" src="https://github.com/user-attachments/assets/7c98ef4e-0623-4930-b4ec-7c15fbe222b5" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152608" src="https://github.com/user-attachments/assets/dff9c39e-b788-4908-8a5c-3469c137a360" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152538" src="https://github.com/user-attachments/assets/8a7fa5c4-ac73-4b04-b1a4-fe729c0a578f" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152523" src="https://github.com/user-attachments/assets/a00de144-9fcc-44a6-b565-e130f9914894" />
<img width="1920" height="1140" alt="Screenshot 2026-06-16 152406" src="https://github.com/user-attachments/assets/1fb3f937-1041-4263-b38a-e328beaddc50" />
<img width="1522" height="1140" alt="Screenshot 2026-06-16 152926 1" src="https://github.com/user-attachments/assets/5f08f788-9313-4420-9bff-731d02c8143d" /><img width="1920" height="1140" alt="Screenshot 2026-06-18 142115" src="https://github.com/user-attachments/assets/a2f38662-2a71-46a8-b45b-a169efb23056" />
<img width="1536" height="1024" alt="ChatGPT Image Jun 18, 2026, 02_24_47 PM" src="https://github.com/user-attachments/assets/22c79813-c3e3-4b9b-819a-8eb2461fe120" />

🔐 AWS Cloud Security Monitoring System (SOC Detection Pipeline)
📌 Overview

This project demonstrates a real-time cloud security monitoring system built on AWS that detects high-risk IAM and account activity and triggers automated security alerts.

The system simulates a lightweight SOC (Security Operations Center) monitoring pipeline using an event-driven AWS architecture.

🧱 Architecture
CloudTrail → CloudWatch Logs → Metric Filters → CloudWatch Alarms → SNS Email Notifications

⚙️ AWS Services Used

AWS IAM (Identity and Access Management)
AWS CloudTrail (Audit logging)
Amazon CloudWatch Logs (Centralised log storage)
CloudWatch Metric Filters (Event pattern detection)
CloudWatch Alarms (Real-time alerting)
Amazon SNS (Email notifications)

🚨 Security Detections

This system detects and alerts on:

Root account console login activity
IAM user creation and deletion
IAM role modifications
Policy attachment and privilege escalation events
📊 How It Works
AWS CloudTrail logs all account activity
Logs are sent to CloudWatch Logs
Metric filters scan logs for suspicious IAM patterns
CloudWatch Alarms trigger when conditions are met
SNS sends real-time email alerts

🧠 What I Learned
Cloud security monitoring fundamentals
IAM event tracking and auditing
CloudWatch log analysis and metric filters
Event-driven security architecture in AWS
SOC-style alerting and detection workflows
🚀 Future Improvements
Add anomaly-based detection (beyond rule-based alerts)
Extend to multi-account AWS environments
Integrate with SIEM tools (Splunk / Microsoft Sentinel)
Add automated incident response (Lambda-based actions)
🔗 Project Purpose

This project was built to simulate how real-world cloud security teams monitor and detect suspicious activity in AWS environments using native security tools.
