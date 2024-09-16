---
title: "Database Access Logs"
categories: ["Database", "Logs", "Data Breach"]
---

These logs capture the sequence of database queries and export actions taken by the attacker.


```
Sep 11 16:00:05 DB-Server-01: Connection established by user 'jdoe_admin' from IP 10.0.3.12.
Sep 11 16:02:47 DB-Server-01: QUERY - SELECT * FROM customer_data WHERE sensitive_info = 'true';
Sep 11 16:03:15 DB-Server-01: QUERY - SELECT COUNT(*) FROM customer_data;
Sep 11 16:04:22 DB-Server-01: QUERY - SELECT email, phone FROM customer_data WHERE opt_out = 'false';
Sep 11 16:05:30 DB-Server-01: EXPORT - User 'jdoe_admin' executed data export script on customer_data table. Export size: 2.3GB.
Sep 11 16:07:40 DB-Server-01: ALERT - High volume of export commands detected for user 'jdoe_admin'. Flagged for review.
Sep 11 16:10:00 DB-Server-01: QUERY - SELECT * FROM encryption_keys WHERE active = 'true';
Sep 11 16:12:15 DB-Server-01: EXPORT - Data export completed successfully. Export transferred to external IP 192.168.210.88.
```