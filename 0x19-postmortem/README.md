0x19-postmortem
Issue Summary:

Duration: Outage lasted 2 hours, from 10:00 AM to 12:00 PM (UTC+0).
Impact: Primary web app completely down, affecting 80% of users.
Root Cause: Load balancer misconfiguration caused uneven traffic distribution.
Timeline:

10:00 AM (UTC+0): Monitoring alerted to server response spike.
10:05 AM: Engineers began investigating, focusing on app servers.
10:15 AM: Shifted focus to load balancer config.
10:30 AM: Misconfig identified, incident escalated.
11:30 AM: Load balancer config corrected, traffic evened.
12:00 PM: App fully restored.
Root Cause and Resolution:

Root Cause: Load balancer misconfig caused traffic imbalance.
Resolution: Load balancer config corrected, traffic evened, service restored.
Corrective and Preventative Measures:

Improvements/Fixes: Regular load balancer audits, enhanced monitoring, automated config checks.
Tasks to Address the Issue: Implement automated config checks, enhance monitoring, conduct regular load testing.
Conclusion:

Outage due to load balancer misconfig, fixed by correcting config. Measures in place to prevent future incidents.
