---
title: "Anonymous Functions in PowerShell"
type: source
tags: [powershell, functional, scriptblocks]
sources: [anonymous-functions-in-powershell]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/basics/Anonymous Functions in PowerShell.md
---

## Summary
Conceptual article explaining script blocks as PowerShell's practical anonymous-function model, including delegate interop, pipeline invocation semantics (`&` vs dot-sourcing), and performance/ergonomic trade-offs relative to `ForEach-Object`.

## Key Claims
- Script blocks act as PowerShell's de facto anonymous functions.
- PowerShell can translate script blocks to delegate-like constructs for .NET APIs.
- Invocation mode (`&` or `.`) changes scope behavior and variable visibility.

## Key Quotes
> "your `{ basic script block }` is the de facto anonymous function in PowerShell"

## Connections
- [[PowerShellBasics]] — foundational language semantics.
- [[FunctionalProgramming]] — functional style and lambda-like behavior.
- [[ScriptBlocks]] — primary construct under discussion.

## Contradictions
- None identified.
