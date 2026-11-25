# Cloud Security Lab

This repository contains hands-on studies and practical exercises focused on AWS Cloud Security.  
The goal is to build a strong foundation in identity, access, monitoring, and secure configurations following industry best practices.

## 🔐 Topics Covered
- Identity and Access Management (IAM)
- Least privilege and policy design
- S3 secure configuration examples
- CloudTrail and CloudWatch basics
- VPC fundamentals and segmentation principles
- Logging, monitoring, and basic detection use cases
- Shared Responsibility Model notes

## 📂 Repository Structure
- aws-iam/
- aws-vpc/
- aws-logging-monitoring/
- aws-s3-security/
- diagrams/
- notes/
- terraform/ — intentionally vulnerable lab infrastructure as code
- scenarios/ — attack → detection → remediation write-ups
- detections/ — cloud detections (Sigma / KQL)
- reports/ — CSPM assessments (Prowler)

## 🎯 Objectives
- Develop practical cloud security skills  
- Demonstrate understanding of secure AWS architecture  
- Build material for a future cloud security portfolio  

## 🧪 Hands-on Roadmap
- [ ] Vulnerable Terraform environment → attack → detection (CloudTrail / GuardDuty) → remediation
- [ ] Prowler assessment of a test account with a remediation plan
- [ ] 5 cloud detections written in Sigma / KQL
- [ ] CI pipeline running Checkov on the Terraform code
- [ ] Azure track: Entra ID, Defender for Cloud and Microsoft Sentinel

> **Cost safety:** every scenario starts with an AWS Budgets alert and ends with `terraform destroy`. Never commit credentials.

## 📝 Notes
This repository evolves as my studies progress. Additional exercises and documentation will be added continuously.
