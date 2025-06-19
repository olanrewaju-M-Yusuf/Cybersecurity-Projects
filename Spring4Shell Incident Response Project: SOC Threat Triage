# Spring4Shell Incident Response Project – SOC Threat Triage

## Project Title  
**Spring4Shell Threat Detection and Notification Protocol for Spring Framework Exploit (CVE-2022-22965)**

---

## 1. Background & Problem Statement  
In April 2022, a critical remote code execution (RCE) vulnerability (CVE-2022-22965) affecting the Spring Framework—known as Spring4Shell—was disclosed. This vulnerability allowed unauthenticated attackers to gain control of servers running Spring Core under specific Java versions and conditions. At the Telstra Security Operations Centre (SOC), a key production system utilizing Spring Core experienced a service outage. Investigation confirmed signs of compromise matching Spring4Shell IOCs. As the information security analyst, you are responsible for triaging the incident, assessing the infrastructure impact, and notifying the appropriate internal team.

---

## 2. Objective
- Analyze firewall logs and infrastructure inventory to identify affected systems
- Classify infrastructure based on criticality and assign priority
- Notify the appropriate team based on threat impact and system importance
- Prepare and send a concise alert email including timestamp and threat context
- Document the incident and mitigation plan for audit and learning purposes

---

## 3. Stakeholders and Responsibilities
| Stakeholder               | Responsibility |
|---------------------------|----------------|
| SOC Analyst               | Triage incident, analyze logs, identify IOCs |
| AppSec Team               | Apply patch/fix, validate integrity of application |
| Infrastructure/Platform   | Support system recovery, configuration validation |
| Legal & Compliance Team   | Ensure reporting and risk alignment |
| CISO                      | Approve response actions and oversee crisis communication |

---

## 4. Incident Triage and Notification Process

### Step 1: Threat Identification
- Based on the CVE (CVE-2022-22965), affected systems include those running:
  - Spring Core on Java 9+ deployed as WAR in Tomcat
  - Systems exposed via HTTP requests without proper sanitization

### Step 2: Infrastructure Impact Review
From the firewall and infrastructure logs provided, the following were identified:
- **Service**: PatientRecordAPI
- **Server**: prod-api-spring-01
- **Timestamp**: 2022-04-01 11:23:46
- **Status**: Unavailable due to exploit
- **Priority**: High (directly impacts healthcare service delivery)

### Step 3: Notification Routing
- The responsible team: **AppSec Team**
- Email crafted using provided Telstra template

---

## 5. Email Notification (Using Provided Template)

**From**: Telstra Security Operations  
**To**: AppSec Team (appsec@telstrahealth.com)  
**Subject**: Immediate Action Required: Spring4Shell Exploit Detected on prod-api-spring-01  

---

**Body**:

Hello AppSec Team,

At **2022-04-01 11:23:46**, a critical service disruption was detected on `prod-api-spring-01` hosting the `PatientRecordAPI`. The disruption matches indicators associated with **Spring4Shell (CVE-2022-22965)**, suggesting potential exploitation.

The service is currently offline, and due to the business-critical nature of this infrastructure (healthcare operations), we have flagged this as a high-priority incident.

Please initiate immediate investigation and remediation per the official guidance from Spring and CISA.

For any questions or issues, don’t hesitate to reach out to us.

Kind regards,  
Telstra Security Operations

---

## 6. Tools & Platforms Used
| Category             | Tool                  | Purpose |
|----------------------|------------------------|---------|
| SIEM & Alerting      | Splunk, AWS GuardDuty | Detect IOCs and correlate logs |
| Firewall & Network   | Palo Alto, Fortinet    | Analyze ingress/egress attempts, apply rule blocks |
| Ticketing            | Jira, ServiceNow       | Track alert resolution and incident tasks |
| Collaboration        | Slack, Microsoft Teams | Internal coordination with AppSec, Infra, Legal |

---

## 7. References (APA 7th Edition)
- CISA. (2022). *Spring Releases Security Updates Addressing Spring4Shell (CVE-2022-22965)*. https://www.cisa.gov/news-events/alerts/2022/04/01/spring-releases-security-updates-addressing-spring4shell-and-spring  
- Spring.io. (2022). *Spring Framework RCE – Early Announcement*. https://spring.io/security/cve-2022-22965  
- MITRE. (2022). *CVE-2022-22965*. https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2022-22965  
- National Institute of Standards and Technology. (2020). *Security and Privacy Controls for Information Systems and Organizations (SP 800-53 Rev. 5)*. https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final

---

> Prepared by: **Rewaju** – Information Security Analyst | Security Operations Centre (SOC)
