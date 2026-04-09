---
title: "Find the Current User Logged on a Remote Computer  Windows OS Hub"
type: source
tags: [powershell, remote, user-session]
sources: [find-the-current-user-logged-on-a-remote-computer-windows-os-hub]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/woshub/Find the Current User Logged on a Remote Computer  Windows OS Hub.md
---

## Summary
Operational reference for determining who is logged onto remote Windows computers using multiple approaches: Sysinternals `psloggedon`, `qwinsta`, WMI/CIM (`Win32_ComputerSystem`), and bulk PowerShell inventory scripts.

## Key Claims
- Different tooling surfaces different session scopes (local console, SMB sessions, RDS sessions).
- WMI/CIM is a straightforward way to retrieve logged-on user context remotely.
- Domain-scale inventory is practical via AD computer enumeration plus connectivity checks.

## Key Quotes
> "an administrator needs to quickly find out the username logged on a remote Windows computer"

## Connections
- [[RemoteOperations]] — remote session-state discovery.
- [[ADAdministration]] — domain-wide machine targeting.
- [[PowerShell]] — remoting/inventory orchestration.

## Contradictions
- None identified.
