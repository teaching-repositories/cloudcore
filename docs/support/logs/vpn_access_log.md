---
title: "VPN Access Logs"
categories: ["VPN", "Logs", "Data Breach"]
---

These logs show the initial access via the VPN using compromised credentials.


```
Sep 11 15:00:03 CCN-VPN-01: User 'jdoe' authenticated from IP 192.168.100.101 via VPN. Authentication method: password.
Sep 11 15:00:05 CCN-VPN-01: MFA check bypassed for user 'jdoe' due to admin-level privilege exception.
Sep 11 15:15:10 CCN-VPN-01: User 'jdoe' session initiated from internal IP 10.0.3.12.
Sep 11 15:30:25 CCN-VPN-01: Suspicious login attempt detected from IP 192.168.105.110; failed MFA for user 'jdoe'. No further action taken.
Sep 11 15:45:30 CCN-VPN-01: User 'jdoe' executed network scan command. Unusual activity detected.
```