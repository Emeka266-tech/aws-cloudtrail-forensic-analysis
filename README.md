# aws-cloudtrail-forensic-analysis
<h2>Cloud security forensic project analyzing AWS CloudTrail logs to detect unauthorized access patterns, investigate incidents, and demonstrate practical SOC-level threat hunting skills.</h2>

# AWS CloudTrail Forensic Analysis (SOC Internship Project)

## Overview

This project is based on a real-world cloud forensic investigation scenario completed during my SOC Analyst internship. The objective was to analyze AWS CloudTrail logs to identify suspicious activity and reconstruct a security breach.

## Key Objectives

* Identify compromised credentials
* Trace attacker activity across logs
* Detect privilege escalation
* Analyze obfuscated (Base64) data
* Investigate data exfiltration
* Identify persistence mechanisms

## Tools Used

* VS Code (log analysis)
* CyberChef (Base64 decoding)
* AWS CloudTrail logs

## Key Findings

* A compromised access key was used from an external IP address
* The attacker escalated privileges using a malicious IAM policy
* Sensitive credentials were exposed via Base64 encoding
* Data was exfiltrated from an S3 bucket
* A backdoor IAM user was created for persistence

## Report

The full investigation report is available in this repository as a PDF.

## Skills Demonstrated

* Cloud Security Analysis
* Threat Hunting
* Incident Response
* Log Analysis
* AWS Security Fundamentals
