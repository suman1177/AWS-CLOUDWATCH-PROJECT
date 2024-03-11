## AWS-PROJECT:  AWS-CLOUD WATCH ALARMING: Custom Metrics for Automated EC2 Termination.
## Project Overview: 
This project demonstrates the creation of an Amazon EC2 instance on AWS with a focus on custom metrics monitoring using AWS Cloud Watch. The primary metric being monitored is CPU Utilization and an automated termination process is configured to trigger when the CPU utilization falls down below a specific threshold over defined duration
## STEPS INVOLVED:
# STEP 1: Launch an EC2 Instance
Creation of EC2 Instance using AWS Management Console.
Configure instance type, security group, networking and other relevant settings.
# STEP 2: CLOUD WATCH ALARM SET-UP
Navigate to Cloud watch service and create a custom alarm.
Set the threshold to 3% CPU Utilization over a 15 min period of time.
# STEP 3: AUTOMATED TERMINATION 
Configure the actions of an alarm for automated termination of EC2 instance when triggered.
Select the action: “Terminate this instance”
# STEP 4: TESTING WITH EC2 CONNECT
Use EC2 connect or other different ways to connect an EC2 instance.
Execute commands to simulate CPU Utilization and trigger the CloudWatch alarm.
# STEP 5: MONITORING 
Regularly check the Cloud Watch Dashboard.
Observe CPU Utilization metrics over time to ensure the configured alarm triggers as expected
