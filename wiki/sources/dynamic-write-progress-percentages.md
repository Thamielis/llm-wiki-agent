---
title: "Dynamic Write-Progress Percentages"
type: source
tags: [powershell, basics, progress]
date: 2026-06-23
source_file: raw/PowerShell/basics/Dynamic Write-Progress Percentages.md
---

## Summary
This source shows how to compute `Write-Progress` percentages dynamically instead of hard-coding each value. The script counts its own `Write-Progress` calls, stores a shared counter, and increments progress as each step runs.

## Key Claims
- Hard-coded progress percentages become brittle when script structure changes
- A script can count its own `Write-Progress` statements with `Get-Content` and a regex match
- A global counter plus the total number of indicators can produce a reusable progress ratio
- The approach works best when each progress step runs once

## Key Quotes
> "This process only works if each write-progress is executed once" — source text

## Connections
- [[PowerShellBasics]] — practical shell scripting pattern for progress feedback
- [[SessionState]] — uses global scope to share progress state across functions
- [[ScriptArchitecture]] — demonstrates a self-aware script structure that depends on internal counting

## Contradictions
- No direct contradiction detected with current wiki pages.
