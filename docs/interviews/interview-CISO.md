---
title: Transcript of interview with CISO
---

Auditor: Thank you for taking the time to meet with me today. As part of the ISO 27001 audit, I'd like to discuss how your organisation handles access controls for information systems. Could you walk me through the key controls in place?

CISO: Of course. We utilise role-based access controls enforced by Active Directory group policies. Employees are granted least privilege access tied to their job roles. We regularly review access and revoke when no longer needed such as for departing employees.

Auditor: That's great to hear. Are there established procedures for provisioning and deprovisioning user access?

CISO: Yes, we have formal onboarding and offboarding checklists that IT staff follow to grant or revoke access when an employee joins or leaves. Access request tickets also document when new access is approved.

Auditor: Excellent. And how often do you review user accounts and access permissions to identify unauthorised or dormant access?

CISO: We run automated reports monthly to show stale accounts and privilege creep. Account owners have to verify or remove access. We also do quarterly entitlement reviews of all high risk systems.

Auditor: That covers some key points around access controls. Let's move on to how you manage security configurations for servers, workstations and other endpoints. Could you outline some of the standards and procedures in place?

CISO: Sure, managing secure configurations is critical for us. We utilise the CIS benchmarks to harden OS settings and have a gold build standard for workstations and servers...


Auditor: Let's discuss vulnerability management. What processes do you have to scan for vulnerabilities and prioritise patching?

CISO: We utilise Tenable.io to perform weekly vulnerability scans on all systems. Critical and high risks are patched within 15 days. We use dedicated windows for production systems.

Auditor: How do you secure sensitive data at rest and in transit across your infrastructure?

CISO: For data at rest, we leverage disk and database encryption. In transit, connections are encrypted TLS 1.2 or greater. We mandate SSH, VPNs, and HTTPS. Sensitive data is anonymised for non-production use.

Auditor: What physical security controls are in place for corporate facilities and data centers?

CISO: We use layered controls including fences, alarms, CCTV, guards, badges, and biometric readers. The data center has mantraps and environment monitoring. Facilities are audited annually.

Auditor: Explain your backup and recovery processes for critical systems and information assets.

CISO: Daily incremental backups to disk onsite, weekly fulls to tape offsite. We have documented recovery plans with RTOs and RPOs. Disaster recovery tests are run twice a year to validate capabilities.

Auditor: How do you evaluate security risks when adopting cloud services or working with vendors?

CISO: Third-party risk assessments are completed analysing data sensitivity, access needs and vendor security posture. Information security terms are incorporated into contracts. Cloud deployments follow our secure architecture guidelines.


Auditor: How do you ensure collaboration between security teams like IT, HR, legal, facilities etc?

CISO: We have regular meetings between department security liaisons to discuss issues and initiatives. I meet individually with each executive regularly. Security committees with cross-functional representation are used for policy and control oversight.

Auditor: What mechanisms exist for security teams to escalate issues or concerns?

CISO Security teams can directly engage my office on any roadblocks or concerns. We have an internal ticketing system to track security escalations and risks if collaboration breaks down. I report up through the infrastructure steering committee on issues needing executive visibility.

Auditor: How are conflicts between business objectives and security priorities resolved?

CISO: We always aim to enable business needs securely. If there are conflicts, we perform risk assessments jointly to understand tradeoffs. Data-driven rationale focusing on business impacts drives decisions. We may implement additional monitoring and review. Executive oversight helps align on approach if needed.