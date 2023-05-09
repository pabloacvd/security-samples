# UC1: Phising
## Description
	User clicked on malicious URL or opened attachment in email.
	URL redirected to a malicious site 
## Actors
	SOC Analyst, HR
## Assumptions
	
## Pre-condition
	
## Steps
	1. EDR triggers an incident.
	2. Check reputation of IoCs.
	3. Query SIEM for more context.
	4. Investigate new IoCs.
	5. If apropriate, block malicious IPs.
	6. If required, isolate the endpoint.
	7. Manual remediation? (redeploy OS image).
	8. Remove email from Exchange server.
