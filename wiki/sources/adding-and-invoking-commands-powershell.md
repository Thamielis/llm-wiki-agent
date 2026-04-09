---
title: "Adding and invoking commands - PowerShell"
type: source
tags: [powershell, hosting, runspaces, api]
sources: [adding-and-invoking-commands-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/RunspaceParallel/Adding and invoking commands - PowerShell.md
---

## Summary
Reference tutorial for building hosted PowerShell pipelines through the .NET API (`PowerShell.Create`, `AddCommand`, `AddParameter`, `AddScript`, and `AddStatement`). It details both synchronous (`Invoke`) and asynchronous (`BeginInvoke`/`EndInvoke`) execution patterns.

## Key Claims
- The `PowerShell` class composes pipelines incrementally through command and parameter builders.
- `AddStatement` breaks pipeline chaining to simulate command batching.
- Asynchronous execution uses `BeginInvoke` and `EndInvoke` with `IAsyncResult`.

## Key Quotes
> "After creating a runspace, you can add Windows PowerShell commands and scripts to a pipeline."

## Connections
- [[PowerShell]] — API and execution host.
- [[Runspaces]] — execution container for hosted pipelines.
- [[ParallelProcessing]] — asynchronous invocation path for concurrent operations.

## Contradictions
- None identified.
