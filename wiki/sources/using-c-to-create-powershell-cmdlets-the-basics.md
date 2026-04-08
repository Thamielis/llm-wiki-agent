---
title: "Using C to Create PowerShell Cmdlets: The Basics"
type: "source"
tags: [powershell, csharp, cmdlets]
sources: [using-c-to-create-powershell-cmdlets-the-basics]
last_updated: "2026-04-08"
date: "2026-04-08"
source_file: "raw/PowerShell/01_Development/Documenting/Using C to Create PowerShell Cmdlets The Basics.md"
---

## Summary
Michael Sorens provides a practical recipe for implementing a PowerShell cmdlet in C#. The article covers the PowerShell reference assemblies, `CmdletAttribute`, `OutputType`, parameter binding, aliases, pipeline input, and output-object design, using a `Get-NetworkAdapter` example. It complements the binary-cmdlet documentation article by showing how the cmdlet itself should be built before it is documented.

## Key Claims
- Writing PowerShell cmdlets in C# is straightforward once the required attributes and assembly references are understood.
- `OutputType` matters both for help metadata and for a better interactive experience such as tab completion.
- Proper parameter metadata and pipeline binding are central to making C# cmdlets feel native in PowerShell.

## Key Quotes
> "the hardest part is finding the information on how to do it"

## Connections
- [[MichaelSorens]] — author walking through the cmdlet recipe.
- [[BinaryCmdlets]] — the cmdlet class this tutorial focuses on.
- [[PowerShell]] — the host environment the C# cmdlet integrates with.
- [[PowerShellDocumentation]] — the article pairs naturally with the documentation sources for binary cmdlets.

## Contradictions
- No direct contradictions with current wiki content.
