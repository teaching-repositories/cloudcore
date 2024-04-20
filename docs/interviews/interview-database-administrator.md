---
title: Transcript of interview with DBA
categories:
      - "Data Security"
      - "IT Management"
      - "Risk Assessment"
---

Auditor: I'd like to understand how database security is handled here. Could you give me an overview of your database architecture?

DBA: Sure. We utilise a mix of open source and commercial databases depending on the use case. Databases are hosted on segmented servers according to sensitivity level and access requirements.

Auditor: Good overview. And how are the databases secured technically?

DBA: Minimised open ports, encrypted connections, CIS benchmark hardening of the servers. The databases themselves have encryption, access controls, and stored procedures to limit exposure.

Auditor: Great to hear. I'm here to have a collaborative discussion about your database controls. If any gaps arise, I'll work through practical recommendations with you. Does that sound good?

DBA: Absolutely, I appreciate you taking that approach. I'm open to constructive feedback on how we can evolve our database security measures.

Auditor: Glad we're aligned. Could you outline your strategies for securing database credentials and controlling access?

DBA: Of course. We utilise a privileged access management solution to rotate credentials and control access to database shells. Access is granted based on least privilege principles...

Here are 5 additional mock interview questions continuing the friendly database security discussion:

Auditor: What controls do you have in place for monitoring database activity?

DBA: Database logging is enabled, as well as triggers for sensitive modification events. Logs feed into our central SIEM. We have a baseline of expected activity and alert on anomalies.

Auditor: Could you explain your backup and recovery strategies for databases?

DBA: Daily differential backups, weekly full backups with retention policies. Critical databases have replicas for high availability. We practice restores and have documented recovery plans.

Auditor: What is your approach to database patching and vulnerability management?

DBA: We classify and test patches in dev environments before rolling out. Vulnerability scans are performed periodically to identify risks. We have a window for production patching.

Auditor: How do you evaluate and secure new database technologies before adoption?

DBA: Our architecture review board assesses capabilities, security, supportability before approval. Security is configured prior to production use per our standards.

Auditor: Finally, what database-specific training exists for your team?

DBA: Vendor training on database hardening, logging, encryption features. Our DBAs are certified on the platforms we use. Security is always emphasised.

Auditor: Are there any difficulties aligning database management needs with security controls?

DBA: At times we have to balance performance and availability needs with strict security controls. With consultation, we usually find solutions like selective encryption or tiered access models.

Auditor: How are database permission conflicts between security team and business users handled?

DBA: We aim to provide the access required for business functions while adhering to least privilege principles. Disagreements are resolved collaboratively through access reviews.

Auditor: Is database activity monitoring effective for security incident alerting?

DBA: Yes, the database logs provide excellent visibility along with our security monitoring capabilities. We are able to quickly detect and alert on anomalous queries or privilege misuse.