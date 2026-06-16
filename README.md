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

