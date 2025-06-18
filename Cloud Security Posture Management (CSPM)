# Cloud Security Posture Management (CSPM)

![image](https://github.com/user-attachments/assets/5fee464f-7dfe-4eaa-b8b0-2abc93775166)

## Project Title
**Enhancing Cloud Security & Compliance through CSPM in Multi-Cloud Environments**

---

## 1. Background & Problem Statement
Cloud misconfigurations and compliance lapses were major concerns for the organization’s growing AWS and Azure cloud environments. Manual processes couldn’t scale, and exposures like public S3 buckets, inconsistent IAM policies, and untagged resources posed regulatory and security threats. This led to the launch of a CSPM project aimed at automating compliance monitoring, reducing misconfigurations, and strengthening incident response workflows.

---

## 2. Objective
- Reduce critical misconfigurations in AWS and Azure by 60%
- Achieve 90% alignment with NIST CSF standards
- Cut mean time to remediate (MTTR) by at least 50%
- Establish automated monitoring and remediation workflows

---

## 3. Stakeholders and Responsibilities
| Stakeholder              | Responsibility                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| CISO                     | Strategic oversight, regulatory alignment, executive reporting                 |
| Cloud Security Engineers | Tool integration, remediation playbooks, IaC scanning                         |
| DevOps Teams             | IaC pipeline integration, secure deployment alignment                         |
| Compliance Officer       | NIST CSF alignment, audit readiness tracking                                   |
| Security Operations (SOC)| Alert triage, SIEM correlation, SOAR playbook development                     |

---

## 4. Frameworks Used
- **NIST Cybersecurity Framework (CSF)**: For maturity measurement and control baseline [(Mell & Grance, 2011)](https://nvlpubs.nist.gov/nistpubs/800-145/SP800-145.pdf)
- **CIS Benchmarks**: Applied during policy enforcement and compliance scanning
- **PCI DSS**: Where applicable to systems handling sensitive cardholder data

---

## 5. Project Implementation Steps

### Phase 1: Discovery & Onboarding
![image](https://github.com/user-attachments/assets/9240847c-44b0-40e5-8686-6802eba52b60)

- Agentless deployment of **Prisma Cloud CSPM** across 12 AWS and 8 Azure accounts
- Integrated over 250 compliance policies, including CIS, NIST, PCI DSS
- Identified 3,400+ misconfigurations including 1,200+ critical issues

### Phase 2: Integration & Automation
![image](https://github.com/user-attachments/assets/5982ddda-2e3d-4a2b-b5d7-aeba699983c2)

- Integrated CSPM alerts into **Splunk SIEM** for centralized visibility
- Built 15 SOAR playbooks in **Phantom** for automated remediation
- Embedded Checkov for Infrastructure-as-Code scanning in CI/CD pipelines

### Phase 3: Continuous Monitoring
- Weekly posture reviews and tagging compliance reporting
- Suppression rules and alert tuning to reduce false positives and alert fatigue
- DevSecOps alignment to ensure misconfigurations are resolved pre-deployment

---

## 6. Key Takeaways
![image](https://github.com/user-attachments/assets/12131283-ff27-446d-a5ef-c0d073d54a2b)

- **SOAR automation** significantly reduced manual remediation workload
- **IaC scanning** empowered shift-left security at the developer stage
- **Cross-functional ownership** (via RACI) streamlined remediation tracking
- **Policy tuning** improved alert signal-to-noise ratio, avoiding burnout
- **Cloud visibility** improved through tagging standards and asset inventory alignment

---

## 7. Outcomes
![image](https://github.com/user-attachments/assets/857f4e6f-9dbf-48eb-8969-2267fecda20a)

- **72% reduction** in critical misconfigurations
- NIST CSF compliance improved from **68% to 93%**
- MTTR dropped **from 48 hours to 15 hours** (68% improvement)
- **85% tagging compliance** enabled more accurate monitoring

---

## 8. Tools & Platforms Used
| Category                  | Tool/Platform             | Purpose                                            |
|---------------------------|----------------------------|----------------------------------------------------|
| CSPM                      | Prisma Cloud              | Misconfiguration detection and policy enforcement  |
| SIEM                      | Splunk                    | Alert correlation and reporting                    |
| SOAR                      | Phantom                   | Automated remediation workflows                    |
| IaC Scanning              | Checkov                   | Code-level misconfiguration detection              |
| Project Management        | Jira                      | Alert assignment, remediation tracking             |
| Reporting/Dashboards      | Power BI                  | Risk and posture trend dashboards                  |

---

## 9. Challenges & Mitigation
![image](https://github.com/user-attachments/assets/cdb744f4-08a6-4dea-8213-31db7bbc21df)

- **Alert fatigue**: Optimized detection policies, suppression rules, alert tuning
- **Integration complexity**: DevOps-Security collaboration for clean API onboarding
- **False positives**: Baseline establishment and iterative tuning sessions

---

## 10. Future Roadmap
![image](https://github.com/user-attachments/assets/b4e6603f-9ede-42da-979f-5e4b61a6050d)

- Expand coverage to **Google Cloud Platform (GCP)**
- Enhance shift-left security via deeper integration with developer pipelines
- Adopt **Cloud Workload Protection Platforms (CWPP)** for runtime security
- Establish business-specific policy templates
- Continuously refine policies as cloud environments evolve

---

## 11. References (APA 7th Edition)
- Coresight Research. (2023). *U.S. Store Openings & Closings 2023*. Coresight.
- Deloitte. (2023). *Holiday Retail Forecast*. Deloitte.
- ENISA. (2020). *Cloud Security Posture Management for SMEs*. European Union Agency for Cybersecurity.
- Gartner. (2020). *Innovation Insight for CSPM*. Gartner Inc.
- Hashizume, K. et al. (2013). *Security issues in cloud computing*. Journal of Internet Services and Applications, 4(1).
- Mell, P., & Grance, T. (2011). *The NIST definition of cloud computing*. NIST SP 800-145.
- Shackleford, D. (2019). *Cloud Security Posture Management*. SANS Institute.

---

> Authored by: **Muhammed Olanrewaju Yusuf**  
> Certified Cybersecurity Analyst
