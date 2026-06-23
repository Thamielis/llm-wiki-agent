---
title: "Get pending updates in Software Center on remote machines - Powershellbros.com"
type: source
tags: [powershell, sccm, patching, wmi]
sources: [get-pending-updates-in-software-center-on-remote-machines-powershellbros-com]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/SCCM/Get pending updates in Software Center on remote machines - Powershellbros.com.md
---

## Summary
Practical script walkthrough for collecting pending SCCM Software Center updates from remote server-core hosts. It queries `root\ccm\clientsdk:CCM_SoftwareUpdate`, translates `EvaluationState` numeric codes into readable states, and exports report output to grid/csv.

## Key Claims
- `CCM_SoftwareUpdate` is sufficient to enumerate applicable pending updates on SCCM clients.
- `EvaluationState` requires explicit translation logic for human-readable reporting.
- Remote collection through `Invoke-Command` enables multi-server patch posture reporting.

## Key Quotes
> "To get all updates that are present in the Software Center we can use Get-WMIObject command and WMI class."

## Connections
- [[SCCM]] — client update data source and schedule model.
- [[SCCMAutomation]] — reporting automation pattern for patch operations.
- [[PowerShell]] — remoting and data transformation runtime.

## Contradictions
- None identified.
