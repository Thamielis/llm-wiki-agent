---
title: "Get list of unhealthy SCOM agents (grey state) using PowerShell - Powershellbros.com"
type: source
tags: [powershell, scom, monitoring, reporting]
sources: [get-list-of-unhealthy-scom-agents-grey-state-using-powershell-powershellbros-com]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/SCCM/Get list of unhealthy SCOM agents (grey state) using PowerShell - Powershellbros.com.md
---

## Summary
Operational monitoring script that uses the OperationsManager module to enumerate unavailable `Microsoft.Windows.Computer` monitored objects and enriches output with management server, AD site, maintenance mode, and health metadata for export.

## Key Claims
- `Get-SCOMMonitoringObject` filtering by `IsAvailable` surfaces unhealthy monitored agents.
- Enriched custom-object output improves operator triage and exportability.
- Running the script on a SCOM server is required for module/context availability.

## Key Quotes
> "Today I want to show you how easily you can get the list of unhealthy SCOM agents using PowerShell."

## Connections
- [[SCOM]] — monitoring platform and cmdlet source.
- [[MonitoringAutomation]] — health triage/reporting workflow.
- [[PowerShell]] — data extraction and transformation runtime.

## Contradictions
- None identified.
