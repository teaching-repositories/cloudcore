---
title: "Firewall Logs"
categories: ["Firewall", "Logs", "Data Breach"]
---

These logs show external connections and potential unauthorised access attempts.

```
Sep 11 16:12:25 Firewall-01: Connection allowed from internal IP 10.0.3.12 to external IP 192.168.210.88 on port 443. Protocol: HTTPS.
Sep 11 16:13:55 Firewall-01: ALERT - Outbound data transfer volume exceeded normal limits for connection from 10.0.3.12.
Sep 11 16:14:40 Firewall-01: Connection attempt blocked from unauthorised IP 192.168.105.110 on port 22. Protocol: SSH.
Sep 11 16:15:30 Firewall-01: Suspicious outbound connection from internal segment detected. Potential data exfiltration path identified.
Sep 11 16:18:00 Firewall-01: ALERT - Continuous outbound connections to untrusted external IPs by 'jdoe_admin'. Severity: Critical.
```