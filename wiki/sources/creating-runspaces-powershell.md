---
title: "Creating Runspaces - PowerShell"
type: source
tags: [powershell, runspaces, hosting]
sources: [creating-runspaces-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/RunspaceParallel/Creating Runspaces - PowerShell.md
---

## Summary
Microsoft hosting documentation overview explaining what runspaces are and why host applications may use default versus custom/constrained runspaces. It frames runspaces as the execution boundary that controls available commands, data, and language constraints.

## Key Claims
- A runspace is the execution environment for hosted PowerShell commands.
- Host applications can choose default runspaces or build constrained custom runspaces.
- `InitialSessionState` is the key object for customizing runspace capabilities.

## Key Quotes
> "A runspace is the operating environment for the commands that are invoked by a host application."

## Connections
- [[PowerShell]] — runtime being embedded and hosted.
- [[Runspaces]] — conceptual focus of this source.

## Contradictions
- None identified.
