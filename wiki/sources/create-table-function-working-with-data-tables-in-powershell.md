---
title: "Create-Table function - working with Data Tables in PowerShell"
type: source
tags: [powershell, data, tables]
date: 2026-06-23
source_file: raw/PowerShell/basics/Create-Table function - working with Data Tables in PowerShell.md
---

## Summary
This article is a second capture of the same `Create-Table` helper and describes the function in nearly identical terms. It focuses on building typed `DataTable` objects from column definitions and using them for structured data handling in PowerShell.

## Key Claims
- The function accepts a table name and a column-name specification
- Column data types can be set inline by using a `/?` suffix
- The resulting `DataTable` can be populated and edited row by row

## Key Quotes
> "The module is based on .NET Framework class “System.Data”." — source text

## Connections
- [[PowerShell]] — the scripting layer used to expose the helper
- [[PowerShellBasics]] — the article is a practical foundational utility piece
- [[PowerShellModules]] — the helper is presented as reusable module code

## Contradictions
- This capture overlaps strongly with the Powershellbros.com version of the same helper.
