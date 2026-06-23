---
title: "How to gather SCCM device collections - Powershellbros.com"
type: source
tags: [powershell, sccm, reporting]
sources: [how-to-gather-sccm-device-collections-powershellbros-com]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/SCCM/How to gather SCCM device collections - Powershellbros.com.md
---

## Summary
Short reporting script that imports the ConfigurationManager module, resolves a target device resource ID, and gathers SCCM collection memberships for reporting output. It demonstrates an automation bridge between SCCM cmdlets and WMI-backed membership data.

## Key Claims
- SCCM PowerShell modules can be used to automate collection membership reporting.
- Combining `Get-CMDevice` with `sms_fullcollectionmembership` yields per-device collection context.
- Script output can be shaped into report-ready custom objects.

## Key Quotes
> "SCCM have it’s own Powershell module which is copied to SCCM folder during installation."

## Connections
- [[SCCM]] — collection and device inventory platform.
- [[SCCMAutomation]] — repetitive reporting automation use case.
- [[PowerShell]] — cmdlet/WMI glue logic.

## Contradictions
- None identified.
