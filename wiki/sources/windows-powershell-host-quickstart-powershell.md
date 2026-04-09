---
title: "Windows PowerShell Host Quickstart - PowerShell"
type: source
tags: [powershell, hosting, runspaces, api]
sources: [windows-powershell-host-quickstart-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/RunspaceParallel/Windows PowerShell Host Quickstart - PowerShell.md
---

## Summary
Official quickstart for embedding PowerShell in .NET host applications using default or constrained runspaces. It demonstrates command composition (`AddCommand`/`AddParameter`) and custom capability restriction through `InitialSessionState` and explicit `SessionStateCmdletEntry` loading.

## Key Claims
- Embedded hosts can expose all commands (default runspace) or a restricted subset.
- Constrained runspaces can improve startup/performance and narrow user capability.
- `InitialSessionState` configuration determines available command surface.

## Key Quotes
> "To host Windows PowerShell in your application, you use the System.Management.Automation.PowerShell class."

## Connections
- [[PowerShell]] — platform being hosted.
- [[Runspaces]] — default/custom runspace modes.
- [[ScriptArchitecture]] — relevance to designing bounded automation interfaces.

## Contradictions
- None identified.
