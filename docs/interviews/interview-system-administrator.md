---
title: Transcript of interview with System Administrator
---

Auditor: Thanks for taking the time to speak with me today. I'd like to discuss the controls you have in place for managing system security configurations. Could you walk me through your configuration hardening standards?

SysAdmin: Sure, we utilise industry standard benchmarks like CIS and NIST to lock down settings for OS, firewalls, databases and more according to best practices. We keep gold images to simplify patching and deployment.

Auditor: Excellent. And how do you ensure consistency and compliance with those standards?

SysAdmin: Our configuration management system scans new systems against the gold benchmark to validate before production. We also run monthly audits to identify any drift or issues.

Auditor: Great to hear. I'm here to understand how your systems are secured in an open discussion. If any gaps arise, I'll work with you on practical recommendations. Does that sound agreeable?

SysAdmin: Absolutely, I look forward to the constructive feedback on where we can improve. We take a continuous learning approach to security and compliance here.

Auditor: Glad we're on the same page. Could you tell me about how you perform patch management and keep systems up-to-date?

SysAdmin: Of course. We classify patches by criticality. Critical and security updates are applied on a 2 week cycle to production after testing...

Auditor: What tools and capabilities do you utilise for monitoring and logging system activity?

SysAdmin: We deploy Sysmon for endpoint logging and have a SIEM collecting logs centrally. Critical systems utilise process monitoring to detect malicious changes.

Auditor: Could you outline the key controls you have in place to secure privileged access to systems?

SysAdmin: Minimising standing privilege access, enforcing MFA for admin accounts, using privilged access management tools for just-in-time elevation. Logs are closely monitored.

Auditor: What is your approach to infrastructure automation and configuration management?

SysAdmin: We utilise Ansible and Terraform to automate deployment, configuration, and management based on code. This reduces human errors and enforces standards.

Auditor: How do you control and track system-level changes to ensure they are authorised and audited?

SysAdmin: Change requests are documented and approved in our ticketing system. Changes made are logged and compared to tickets for audit purposes.

Auditor: Finally, how do you ensure disaster recovery capabilities for critical systems?

SysAdmin: Documented recovery plans, regular backups to secondary sites. Annual DR tests validate ability to meet RTO/RPO with failover. Gaps are addressed in remediation plans.

Auditor: Do you have any difficulties implementing security guidance from infosec teams?

SysAdmin: Generally no, we view security collaboration as necessary and beneficial. There can be tension around legacy systems where controls introduce availability/performance risks. But with consultation we determine workarounds.

Auditor: How are priority conflicts between operations and security handled?

SysAdmin: Health and availability needs take precedence where reasonable. We perform risk analysis jointly and identify solutions together - perhaps delaying patches, implementing compensating controls or accepting risks with approval.

Auditor: Are there any gaps in training or knowledge transfer between sysadmin and infosec teams?

SysAdmin: Knowledge sharing occurs informally via meetings and tickets. More formalised cross-training could be beneficial though to expand skills. Shadowing and job rotations could help strengthen the partnership and understanding between our teams.