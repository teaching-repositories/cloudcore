---
title: Transcript of interview with Network Engineer
---

Auditor: I'd like to discuss the network security controls you have in place. Could you give me an overview of your network architecture?

Network Engineer: Certainly. We utilise a segmented architecture based on business units and system types. Critical assets are in a separate sone with ACLs limiting access. Edge firewalls provide filtering.

Auditor: Good to hear. How do you monitor and protect against malicious network activity?

Network Engineer: Intrusion detection sensors analyse traffic patterns and alert on known bad signatures. We also capture netflow data and use a SIEM for visibility. Access to monitoring tools is tightly controlled.

Auditor: Excellent. And could you outline some of your network access and authentication controls?

Network Engineer: 802.1x and Radius enforce access policies and restrictions on ports. Wireless uses WPA2 encryption at minimum. VPN concentrators allow MFA protected remote access into business systems. The network is fully switched with protected infrastructure management.

Auditor: That provides a solid baseline. I'm here to have an open discussion about network security. If any potential gaps arise, I'll work through recommendations with you. Does that sound good?

Network Engineer: Absolutely, I welcome the feedback on improving our security posture. Our network is constantly evolving and I want to stay ahead of emerging threats.

Auditor: Could you outline your remote access capabilities and security controls?

Network Engineer: VPN access with MFA for employees. Site-to-site VPNs with partners using encryption and mutual authentication. Remote access is restricted based on least privilege and logged.

Auditor: What protections do you have against DDoS attacks or network flooding scenarios?

Network Engineer: Our internet edge has DDoS prevention scrubbing high volume attacks before they hit internal infrastructure. Rate limiting and ACLs also help minimise impact.

Auditor: How do you perform vulnerability scanning and penetration testing on the network environment?

Network Engineer: Quarterly internal and external vulnerability scans, including from wireless perspectives. Annual third-party pen testing under the guidance of our infosec team.

Auditor: What capabilities exist for network traffic monitoring, capture and analysis?

Network Engineer: We utilise full packet capture and taps to feed network detection systems. Flow data gives us visibility into communications between systems.

Auditor: Finally, could you speak about the redundancy built into the network in case of device failure?

Network Engineer: Redundant internet links, load balancing firewalls, cluster router configurations. We design availability into the architecture for high uptime. Maintenance is scheduled to limit impact.

Auditor: How are network access issues escalated and resolved with security teams?

Network Engineer: We engage infosec on access change tickets if there are questions or potential risks. My team meets regularly with security to review network ACLs and firewall rules for appropriate controls.

Auditor: Do network changes ever get pushed back due to security concerns?

Network Engineer: Yes occasionally, we then work jointly to determine alternative solutions. An example is implementing a DMZ or additional monitoring rather than opening access.

Auditor: Is collaboration effective between network and security ops teams?

Network Engineer: Collaboration is generally strong as the groups need to work very closely. Minor misalignments on priorities which are worked through. Overall we support each other in enabling secure network operations.