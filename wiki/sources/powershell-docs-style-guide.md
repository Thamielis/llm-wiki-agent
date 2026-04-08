---
title: "PowerShell-Docs Style Guide"
type: "source"
tags: [powershell, documentation, style-guide]
sources: [powershell-docs-style-guide]
last_updated: "2026-04-08"
date: "2024-11-08"
source_file: "raw/PowerShell/01_Development/Documenting/PowerShell-Docs style guide - PowerShell.md"
---

## Summary
The PowerShell-Docs style guide codifies how official PowerShell documentation should format syntax, examples, parameter references, and About topics. It standardizes details like lowercase keywords, full cmdlet names, explicit parameter names, fenced code blocks, and the schema expectations imposed by [[PlatyPS]]. Within the current corpus it serves as the strongest normative source for how PowerShell documentation should read and render.

## Key Claims
- PowerShell documentation should prefer full cmdlet and parameter names, explicit syntax, and fenced code blocks.
- Aliases, positional parameters, and prompt strings should be used sparingly because they reduce clarity.
- Cmdlet reference articles must follow the structural constraints expected by [[PlatyPS]].

## Key Quotes
> "Don't use aliases in examples"

## Connections
- [[PowerShellDocumentation]] — the main concept being normalized.
- [[PlatyPS]] — the schema and tooling the style guide relies on.
- [[CommentBasedHelp]] — related because command help structure feeds downstream docs generation.
- [[PowerShell]] — the language whose documentation conventions are being specified.

## Contradictions
- The article is stricter than some older community examples in the corpus, but it does not directly contradict their core technical claims.
