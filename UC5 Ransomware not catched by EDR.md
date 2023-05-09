# UC2: ContiRansomware - Not detected by EDR
## Description
	Users report to help desk that ransom screens are shown on their endpoints.
## Actors
	Help Desk, SOC team
## Assumptions
	1. EDR didn't catch the malware.
## Pre-condition
	1. Not known signature for the malware.
## Steps
	1. Help desk accesses CP4S and creates a case to report the incident.
	2. Analyst investigates on Threat Intelligence Insights about the known IoCs of the ransomware.
	3. Analyst runs a federated search on the EDR and SIEM to find affected endpoints.
## Alternative path
	1. Help desk creates a ticket in a ticketing system, which is connected to CP4S and the case is automatically created.
