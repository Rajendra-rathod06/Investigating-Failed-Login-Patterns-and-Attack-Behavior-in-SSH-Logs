# Investigating-Failed-Login-Patterns-and-Attack-Behavior-in-SSH-Logs
This project focuses on analyzing Linux SSH authentication logs to identify failed login attempts, detect suspicious attack behavior, and understand common authentication-based threats.
By examining SSH log data, the project demonstrates how Security Operations Center (SOC) analysts investigate authentication events, identify brute-force attacks, detect unauthorized access attempts, and generate actionable security insights.

The analysis includes identifying repeated failed login attempts, suspicious source IP addresses, targeted user accounts, login timestamps, and attack trends. The findings help improve security monitoring, incident response, and access control by enabling early detection of malicious authentication activity.

Objectives

Understand SSH authentication and Linux authentication logs.
Parse raw SSH logs into structured Splunk fields.
Detect brute-force attacks, credential stuffing, user enumeration, and account compromise.
Correlate authentication events across users, hosts, and source IP addresses.
Improve detection accuracy and reduce investigation time.
Demonstrate a SOC-ready workflow for authentication log analysis.

Key Features

SSH authentication log analysis
Failed login pattern investigation
Brute-force attack detection
Credential stuffing detection
User enumeration detection
Account compromise detection
Structured field extraction using Splunk
Security event correlation
SOC investigation workflow

Technologies Used

Splunk Enterprise
Linux Authentication Logs (auth.log / secure)
SSH
SPL (Search Processing Language)
Git & GitHub
Attack Scenarios Covered
Brute Force Attack
Credential Stuffing
User Enumeration
Account Compromise (Failed Logins Followed by Successful Login)

Skills Demonstrated

SOC Monitoring
Security Log Analysis
Threat Hunting
Incident Investigation
Authentication Log Analysis
Linux Security Monitoring
Detection Engineering
Splunk Query Development
Learning Outcomes

This project demonstrates how structured log analysis transforms raw SSH authentication logs into actionable security insights. It highlights practical SOC techniques for detecting authentication-based attacks, correlating suspicious events, identifying compromised accounts, and improving incident response through effective log analysis and threat detection.

