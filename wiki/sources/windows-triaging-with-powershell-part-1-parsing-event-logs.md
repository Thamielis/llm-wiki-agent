---
title: "Windows Triaging with Powershell - Part 1 - Parsing Event Logs"
type: source
tags: [powershell, triage, event-logs, forensics]
sources: [windows-triaging-with-powershell-part-1-parsing-event-logs]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/Windows Troubleshooting/Windows Triaging with Powershell — Part 1 Parsing Event Logs.md
---

## Summary
Part 1 triage walkthrough focused on Windows event-log parsing with PowerShell across Application, Security, and System logs, plus entry-type filtering and scripted report generation. It frames event logs as a central timeline source for system and user activity reconstruction.

## Key Claims
- Event logs are core evidence sources for triage and incident reconstruction.
- `Get-EventLog` with log/entry-type filters enables structured extraction.
- Scripting repetitive log queries increases consistency and reporting speed.

## Key Quotes
> "Event Logs play an important role in determining a timeline of various User and System activities"

## Connections
- [[WindowsTroubleshooting]] — triage workflow foundation.
- [[NetworkDiagnostics]] — complementary investigation stream.
- [[PowerShell]] — log parsing and report automation runtime.

## Contradictions
- None identified.
