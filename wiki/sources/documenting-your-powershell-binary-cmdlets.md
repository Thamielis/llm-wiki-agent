---
title: "Documenting Your PowerShell Binary Cmdlets"
type: "source"
tags: [powershell, documentation, csharp]
sources: [documenting-your-powershell-binary-cmdlets]
last_updated: "2026-04-08"
date: "2026-04-08"
source_file: "raw/PowerShell/01_Development/Documenting/Documenting Your PowerShell Binary Cmdlets.md"
---

## Summary
Michael Sorens explains the documentation gap between scripted PowerShell functions and binary cmdlets implemented in C#. The article argues that MAML-based help used to make binary cmdlets painful to document, and presents [[XmlDoc2CmdletDoc]] as the missing bridge from ordinary C# XML doc comments to PowerShell help. The practical result is that C# cmdlets can now participate in the same help-first workflow that PowerShell authors expect from script modules.

## Key Claims
- Binary cmdlets have historically been much harder to document well than script cmdlets.
- [[XmlDoc2CmdletDoc]] lets authors generate MAML from standard C# XML documentation comments.
- Keeping documentation next to code is essential for keeping help accurate over time.

## Key Quotes
> "Binary cmdlets need no longer be the poor cousins of scripted cmdlets in their documentation"

## Connections
- [[MichaelSorens]] — author focused on PowerShell documentation tooling.
- [[XmlDoc2CmdletDoc]] — the utility the article centers on.
- [[PowerShellDocumentation]] — the larger documentation problem space.
- [[BinaryCmdlets]] — the specific cmdlet category under discussion.

## Contradictions
- No direct contradictions with current wiki content.
