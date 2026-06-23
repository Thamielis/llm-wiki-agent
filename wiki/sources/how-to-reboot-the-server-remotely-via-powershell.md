---
title: "How to reboot the server remotely via PowerShell"
type: source
tags: [powershell, remote, reboot]
sources: [how-to-reboot-the-server-remotely-via-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/Remote/How to reboot the server remotely via PowerShell.md
---

## Summary
Short operational note comparing remote reboot approaches: `shutdown.exe`, `Restart-Computer`, and a `New-PSSession` fallback for RPC-unavailable scenarios. The guidance focuses on emergency remediation when out-of-band management paths are unavailable.

## Key Claims
- Multiple remote-reboot paths are needed because RPC-based approaches can fail.
- PSSession-based restart execution can recover situations where direct restart calls fail.
- Session lifecycle cleanup (`Remove-PSSession`) is part of safe remote operation hygiene.

## Key Quotes
> "New-PSSession option comes to our rescue"

## Connections
- [[RemoteOperations]] — remote reboot remediation playbook.
- [[ScriptOrchestration]] — session creation/invoke/cleanup sequence.
- [[PowerShell]] — remote management channel.

## Contradictions
- None identified.
