---
title: "Windows Triaging with Powershell - Part 2 - Artifacts Collection"
type: source
tags: [powershell, triage, artifacts, forensics]
sources: [windows-triaging-with-powershell-part-2-artifacts-collection]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/Windows Troubleshooting/Windows Triaging with Powershell — Part 2 Artifacts Collection.md
---

## Summary
Part 2 expands triage from logs to broad artifact collection (processes, services, network data, user/group info, startup modules, caches, USB/history traces, SMB, apps, defender/notification data), using native PowerShell/CMD tooling and WMI classes.

## Key Claims
- Rapid artifact collection from a live powered-on host is critical for IR/forensics workflows.
- WMI classes and built-in cmdlets cover wide operational/forensic artifact surfaces.
- CSV/exportable outputs improve downstream analysis repeatability.

## Key Quotes
> "Forensic and Incident Response teams would benefit greatly from this approach to gather artifacts as quickly as possible."

## Connections
- [[WindowsTroubleshooting]] — end-to-end triage process.
- [[RemoteOperations]] — relevance to live-host collection contexts.
- [[PowerShell]] — collection and export engine.

## Contradictions
- None identified.
