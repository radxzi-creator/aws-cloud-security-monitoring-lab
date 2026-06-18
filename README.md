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


STep 2

<img width="1920" height="1140" alt="Screenshot 2026-06-18 142115" src="https://github.com/user-attachments/assets/dff461ba-cd9c-4ebd-acc2-f300b45052e8" />
<img width="1536" height="1024" alt="ChatGPT Image Jun 18, 2026, 02_24_47 PM" src="https://github.com/user-attachments/assets/1865bae2-f284-41cb-a1f4-b003b5c42aef" />

## 🔐 Cloud Security Monitoring Lab (Real-Time Detection)

This project builds a real-time cloud security monitoring system using AWS services to detect and alert on suspicious IAM and console activity.

### 🧠 What I built

I configured a CloudTrail + CloudWatch Logs security pipeline that detects high-risk actions in an AWS account, including:

- Root user console logins
- IAM user creation and deletion
- Policy attachment and privilege changes
- Suspicious administrative activity

---

### 🏗️ Architecture

![AWS Security Architecture](a_clean_infographic_architecture_diagram_on_a_wh.png)

---

### ⚙️ AWS Services Used

- AWS CloudTrail (event logging)
- Amazon CloudWatch Logs (central log storage)
- CloudWatch Metric Filters (pattern detection)
- CloudWatch Alarms (real-time alerting)
- IAM (security event source)

---

### 🚨 Detection Rules

- Root Console Login → triggers security alert
- IAM changes (Create/Delete/Attach Policy) → triggers IAM security alarm
- Pattern-based log filtering using CloudWatch Insights

---

### 📊 Outcome

- Real-time detection of privileged account activity
- Security monitoring foundation similar to SOC environments
- Automated alerting capability for suspicious behavior

---

### 🔥 Skills Demonstrated

Cloud Security • AWS IAM • Logging & Monitoring • Threat Detection • SIEM-style thinking • Security Automation
