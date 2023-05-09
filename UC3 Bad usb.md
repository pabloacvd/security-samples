# UC3: BadUSB
## Description
	User plugs a usb, powershell script runs, connects to outside, downloads a dropper.
## Actors
	SOC Analyst
## Assumptions
	1. USB ports are enabled.
	2. Powershell scripts can run as admin on a few Windows endpoints.
## Pre-condition
	1. There is an EDR in place that can detect a malware running in the endpoint. It doesn't filter downloads.
	2. There is no NDR (network analysis) that inspects traffic.
	3. There is no antimalware actively scanning files.
## Steps
	1. An alert is received by the analyst from QRadar SIEM (EDR/AV detected a malware dropper and was put in quarantine).
	2. Analyst uses DataExplorer to find if any other endpoint has seen the dropper.
	3. Dropper is found and a case is created.
	4. Case instructs the analyst to remove the files.
	