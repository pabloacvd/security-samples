# UC1: user no active for 6 months with new activity
## Description
	A user that has not been active for 6 months suddenly starts to connect to critical systems and also uses SaaS storage solutions. SIEM alert for potential massive data exfiltration.
## Actors
	SOC Analyst
## Assumptions
	1. 
## Pre-condition
	1. There is no NDR (network analysis) that inspects traffic.
## Steps
	1. An alert is received by the analyst from QRadar SIEM.
	2. create a case 
	3. ticket to HR to check if it was someone that had a maternity/paternity time off for example.
	4. block access?
	