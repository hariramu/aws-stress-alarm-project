# AWS CloudWatch Alarm Triggered via EC2 CPU Load

## Overview
This project demonstrates how to:
- Launch an EC2 instance using Launch Template
- Set up an Application Load Balancer and Target Group
- Configure Auto Scaling Group (ASG)
- Create a CloudWatch Alarm to monitor CPU usage
- Trigger notifications using Amazon SNS

## Structure
- **stress-command.txt** – The command used to simulate high CPU load
- **screenshots/** – Visuals showing CloudWatch alarm, email alert, EC2 usage

## Architecture

Below is the visual representation of the AWS infrastructure used:
![Architecture Diagram](https://github.com/user-attachments/assets/9e22837e-b8c8-4a2e-bad8-07b5e57553ca)


## Outcome
The CloudWatch alarm successfully triggered an SNS email notification when CPU exceeded the threshold, as shown in the screenshots.

---

📩 Check `stress-command.txt` for the exact testing command used.
