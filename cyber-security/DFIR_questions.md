# Table of Contents

- Memory Analysis(#memory-analysis)
- Timeline Analysis (#timeline-analysis)
- Windows Artifacts (#windows_artifacts)
- Incident Response (#incident_response)

## Memory Analysis
1. When to use memory analysis?
	- Where to collect memory data?
	- Why some registries only acquired in memory
	- What we can dump from memory? 
	- How to acquire password in memory?

## Timeline Analysis
1. What difference from supertimetine and filesystem timeline?

2. What makes timeline analysis beyond just collecting artifacts? Context

3. Why timestamp of *Copy* is A.B but these of *Cut and Paste* is just A?

4. How to use Pivot Point?

5. Why some timestamp in FAT always in 12:00 AM?

6. How timestamp will be change when change timezone in FAT?
	- And in NTFS?

## Windows Artifacts
1. What is registries?
	- What in NTUSER.dat differ from other config/hives
2. Are there quickwin artifacts?
	- How to recognize program execution, file download or file opening?
3. How to combine event log sources in source and target of Lateral Movement actions?
4. Why services in 7045 be randomize?

## Incident Response
1. How to collect information on large scale?
	- Why use PowerShell?
