---
title: "Calling Async .NET Methods from PowerShell"
type: source
tags: [powershell, dotnet, async]
date: 2026-06-23
source_file: raw/PowerShell/basics/Calling Async .NET Methods from PowerShell.md
---

## Summary
This article explains how to call async .NET methods from PowerShell even though PowerShell has no `async` or `await` keywords. It shows the `GetAwaiter().GetResult()` pattern and introduces a `Wait-Task` helper with an `await` alias for waiting on one or more tasks.

## Key Claims
- Async .NET methods return `Task` objects that must be awaited explicitly from PowerShell
- `GetAwaiter().GetResult()` is the direct way to retrieve a task result and surface exceptions
- A small helper function can make awaiting tasks more ergonomic in PowerShell

## Key Quotes
> "PowerShell does not provide an async or await keyword." — source text

## Connections
- [[PowerShell]] — the language runtime being extended with .NET async calls
- [[ParallelProcessing]] — the article touches the broader need for non-blocking execution patterns
- [[Runspaces]] — the surrounding ecosystem for concurrent PowerShell execution

## Contradictions
- No direct contradiction detected with current wiki pages.
