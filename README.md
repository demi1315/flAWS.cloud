# 🔐 flAWS.cloud – AWS Cloud Security Misconfiguration Exploitation

A hands-on **cloud security learning project** focused on identifying and understanding common **AWS misconfigurations** using the intentionally vulnerable **flAWS.cloud** lab.

This project demonstrates practical exposure to **AWS IAM analysis, S3 misconfigurations, access control weaknesses, and cloud reconnaissance**, from a defensive and educational perspective.

---

## 🎯 Project Overview

Cloud misconfigurations are one of the most common causes of data exposure incidents.  
This project uses the *flAWS.cloud* training environment to study how insecure AWS configurations can lead to security risks and how such issues can be identified during a cloud security assessment.

**The main goals of this project are to:**

- Understand real-world AWS misconfiguration scenarios  
- Learn cloud reconnaissance techniques  
- Analyze IAM and S3 security weaknesses  
- Study privilege escalation concepts  
- Build a defensive cloud-security mindset  

---

## 🚀 Key Learning Outcomes

- Understanding AWS Identity and Access Management (IAM)
- Identifying insecure S3 bucket configurations
- Analyzing exposed credentials and permissions
- Learning privilege escalation paths conceptually
- Practicing cloud security reconnaissance
- Mapping findings to security best practices
- Improving defensive cloud security knowledge

---

## 📌 Scope of Assessment

The following areas were analyzed during this project:

- AWS IAM misconfigurations  
- Publicly accessible S3 buckets  
- Over-permissive IAM policies  
- Insecure access key handling  
- Trust relationship misconfigurations  
- Cloud resource enumeration  
- Visibility and monitoring gaps  

---

## 🔍 Misconfiguration Categories Studied

### Identity & Access Management (IAM)
- Overly permissive IAM policies  
- Wildcard (`*`) permissions  
- Weak or misconfigured trust relationships  
- Missing least-privilege enforcement  
- Improper role separation  

### Storage Security (Amazon S3)
- Public bucket exposure  
- Missing Block Public Access settings  
- Insecure bucket policies  
- Data exposure risks  

### Credential Handling
- Exposed or poorly managed access keys  
- Long-lived credentials  
- Excessive permissions attached to keys  
- Lack of credential rotation  

### Monitoring & Visibility
- Limited logging visibility  
- Missing alerting mechanisms  
- Lack of centralized monitoring  

---

## 🧪 Methodology Followed

The assessment was performed using a structured, ethical approach similar to real-world cloud security reviews.

### 1. Reconnaissance
- Identified publicly accessible AWS-related artifacts  
- Enumerated exposed resources  
- Reviewed configuration metadata  
- Studied service relationships  

### 2. Access Analysis
- Analyzed IAM permissions and policy scope  
- Reviewed role trust relationships  
- Evaluated access boundaries  

### 3. Misconfiguration Validation
- Verified misconfigured access paths  
- Confirmed exposure impact  
- Categorized findings by severity  

### 4. Security Analysis
- Mapped findings to AWS security best practices  
- Linked issues to OWASP Cloud risks  
- Documented root causes  

---

## 🛠️ Tools & Technologies Used

- AWS CLI  
- Linux environment  
- `curl`  
- `jq`  
- Amazon S3  
- AWS IAM  
- Cloud security concepts  

---

## 📊 Key Findings Summary

| Area | Observation |
|------|-------------|
| IAM Policies | Over-permissive permissions identified |
| S3 Buckets | Public or misconfigured access observed |
| Credentials | Exposure risk detected |
| Access Control | Weak role separation |
| Monitoring | Limited visibility and alerts |
| Overall Posture | Insecure by default |

---

## 🛡️ Security Recommendations (High-Level)

### IAM Security
- Apply the principle of least privilege  
- Avoid wildcard permissions  
- Use IAM roles instead of long-term access keys  
- Rotate credentials regularly  
- Audit IAM policies periodically  

### S3 Security
- Enable **Block Public Access**
- Use bucket policies instead of ACLs  
- Enable encryption at rest  
- Enable access logging  

### Monitoring & Detection
- Enable AWS CloudTrail  
- Monitor IAM and S3 activity  
- Configure alerts for suspicious actions  
- Use GuardDuty for threat detection  

### Governance
- Perform periodic cloud security reviews  
- Maintain asset inventory  
- Apply AWS Well-Architected Framework principles  

---


## 🚀 Getting Started

### Prerequisites
- Basic AWS knowledge  
- Linux environment  
- AWS CLI installed  
- Understanding of cloud security fundamentals  

### Lab Access

https://flaws.cloud/


> This is a deliberately vulnerable lab designed for learning and security research.

---

## ⚠️ Ethical Disclaimer

This project was conducted **strictly for educational and defensive purposes** using a purposely vulnerable training environment.

- No real-world systems were attacked  
- No unauthorized access was performed  
- No production data was involved  
- Content is intended for learning and awareness only  

---

## 📚 References

- https://flaws.cloud  
- AWS Security Best Practices  
- AWS IAM Documentation  
- AWS S3 Security Guide  
- OWASP Cloud Top 10  
- NIST Cloud Security Framework  

---

## ⭐ Why This Project Matters

This project demonstrates my ability to:

- Analyze cloud misconfigurations methodically  
- Understand AWS IAM and S3 security risks  
- Perform cloud security assessments  
- Document findings professionally  
- Apply defensive security thinking  
- Align work with industry security standards  

---

This repository forms part of my cybersecurity portfolio and showcases practical experience in AWS cloud security assessment, misconfiguration analysis, and defensive security principles.


