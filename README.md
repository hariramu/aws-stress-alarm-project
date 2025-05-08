# AWS CloudWatch Alarm Trigger via Stress Test on EC2

This mini project demonstrates how to:

- Launch EC2 using Launch Template
- Create Application Load Balancer + Target Group + Auto Scaling Group
- Set up CloudWatch alarms for CPU threshold
- Trigger SNS email alerts when CPU > 20%
- Use `stress` command inside EC2 to simulate CPU load

## Stress Command Used:
```bash
sudo amazon-linux-extras install epel -y
sudo yum install stress -y
stress --cpu 1 --timeout 180
