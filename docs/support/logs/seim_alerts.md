---
title: "Security Information and Event Management (SIEM) Alerts"
categories: ["Security Information and Event Management (SIEM)", "Alerts", "Logs", "Data Breach"]
---

These logs detail alerts triggered by the SIEM system.

```
Sep 11 16:05:50 CCN-SIEM-01: ALERT - Multiple database export commands detected for user 'jdoe_admin'. Severity: High.
Sep 11 16:07:52 CCN-SIEM-01: ALERT - Unusual outbound traffic detected to IP 192.168.210.88. Potential data exfiltration.
Sep 11 16:10:30 CCN-SIEM-01: WARNING - Failed login attempts for 'jdoe_admin' from unauthorized IP 192.168.105.113. Possible credential stuffing.
Sep 11 16:15:00 CCN-SIEM-01: CRITICAL - Potential insider threat identified: User 'jdoe_admin' performing actions outside normal behavior profile.
Sep 11 16:20:45 CCN-SIEM-01: NOTIFICATION - Correlation rule triggered for high-risk activity across database, VPN, and network systems.
Sep 11 16:30:12 CCN-SIEM-01: ALERT - External connection to database without encryption detected. Immediate review recommended.
```