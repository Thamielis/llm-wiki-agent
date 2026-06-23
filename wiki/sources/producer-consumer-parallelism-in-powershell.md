---
title: "Producer Consumer Parallelism in PowerShell"
type: source
tags: [powershell, parallelism, runspaces, performance]
sources: [producer-consumer-parallelism-in-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/RunspaceParallel/Producer Consumer Parallelism in PowerShell.md
---

## Summary
Lee Holmes describes a producer-consumer runspace pattern used to accelerate Scour indexing, including work queues, worker threads, and progress tracking. The article demonstrates how concurrent queues and background PowerShell instances can materially improve throughput for many small work items.

## Key Claims
- Producer-consumer orchestration improves high-volume PowerShell work distribution.
- Concurrent queues make it practical to dispatch and collect thread work safely.
- Real-world performance gains came from removing bottlenecks and adding runspace-based parallelism.

## Key Quotes
> "One approach to this is the Producer-Consumer pattern."

## Connections
- [[LeeHolmes]] — author and practitioner reference.
- [[ParallelProcessing]] — core architecture pattern discussed.
- [[Runspaces]] — mechanism used to execute workers concurrently.

## Contradictions
- None identified.
