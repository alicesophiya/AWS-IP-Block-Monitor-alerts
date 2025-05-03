# AWS-IP-Block-Monitor-alerts
AWS WAF IP Block Monitoring with Notifications Objective The goal of this project is to set up a system to monitor blocked IPs in AWS WAF and send real-time notifications using Amazon SNS when an IP is blocked.

#Objective
The goal of this project is to set up a system to monitor blocked IPs in AWS WAF and send real-time
notifications using Amazon SNS when an IP is blocked.

#Architecture Overview
AWS WAF IP Block Monitoring with Notifications
Objective
The goal of this project is to set up a system to monitor blocked IPs in AWS WAF and send real-time
notifications using Amazon SNS when an IP is blocked.
Architecture Overview
1. Application Load Balancer (ALB): Distributes incoming traffic across multiple targets to ensure
high availability.
2. AWS WAF: Protects your web applications by blocking malicious IPs or requests based on rules.
3. CloudWatch Logs: Captures logs from WAF to monitor blocked actions.
4. Metric Filters: Identifies patterns in the logs (e.g., blocked IPs) and creates metrics.
5. CloudWatch Alarms: Monitors the metric and triggers an alarm when a threshold is met.
6. Amazon SNS: Sends notifications (e.g., email) when the alarm is triggered.

