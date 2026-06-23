---
title: "Uninstall applications on multiple machines - Powershellbros.com"
type: source
tags: [powershell, remote, software, wmi]
sources: [uninstall-applications-on-multiple-machines-powershellbros-com]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/Remote/Uninstall applications on multiple machines - Powershellbros.com.md
---

## Summary
Batch uninstallation workflow that consumes CSV input (`ServerName`, `ApplicationName`), queries `Win32_Product` remotely, and classifies outcomes into removed/not-removed/not-found result arrays. The script highlights practical applicability despite acknowledged WMI performance limitations.

## Key Claims
- CSV-driven remote uninstall orchestration enables straightforward multi-host rollout/removal actions.
- Explicit result buckets improve follow-up handling for failures and missing installs.
- WMI `Win32_Product` approach works functionally but may be slow at scale.

## Key Quotes
> "As an input for script CSV file should be provided."

## Connections
- [[RemoteOperations]] — remote software lifecycle actions.
- [[ScriptArchitecture]] — helper-function plus categorized-result design.
- [[PowerShell]] — automation runtime.

## Contradictions
- None identified.
