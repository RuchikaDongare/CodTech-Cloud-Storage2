 Task 2: Cloud Monitoring & Alerts using AWS CloudWatch

EC2 Instance
- AMI: Amazon Linux 2023 (x86)
- Instance Type: t3.micro (Free Tier)
- Key Pair: cloudwatch-key.pem
- Security Group: SSH allowed (0.0.0.0/0)

Steps Performed
1. Launched EC2 instance
2. Connected via SSH using Public IP
3. Installed stress tool and generated CPU load
4. Created CloudWatch CPU Utilization Alarm (>70%)
5. Configured SNS Topic and Email alerts
6. Verified email alert received
7. Created CloudWatch Dashboard with CPU, Network In, and Disk metrics

Screenshots
![EC2 Instance Running](https://github.com/RuchikaDongare/CodTech-Cloud-Storage2/blob/2cc04b983ddd4d50963ddc7c7feffde898bd50c5/Task%202/EC2%20Instances.png)
![CPU Alarm Created](https://github.com/RuchikaDongare/CodTech-Cloud-Storage2/blob/2cc04b983ddd4d50963ddc7c7feffde898bd50c5/Task%202/HIGHCPU_ALARM.png)
![SNS Email Alert](https://github.com/RuchikaDongare/CodTech-Cloud-Storage2/blob/27422e0b9f7556431fe10c9a66603183200013f1/Task%202/HIGH_ALARm_MAIL.jpeg)
![CloudWatch Dashboard](https://github.com/RuchikaDongare/CodTech-Cloud-Storage2/blob/27422e0b9f7556431fe10c9a66603183200013f1/Task%202/CloudWatch_dashboard.png)
