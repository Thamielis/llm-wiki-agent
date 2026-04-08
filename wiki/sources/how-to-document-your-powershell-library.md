---
title: "How To Document Your PowerShell Library"
type: "source"
tags: [powershell, documentation, html]
sources: [how-to-document-your-powershell-library]
last_updated: "2026-04-08"
date: "2026-04-08"
source_file: "raw/PowerShell/01_Development/Documenting/How To Document Your PowerShell Library.md"
---

## Summary
This article extends PowerShell documentation from per-command help into a full browsable API tree. Michael Sorens presents [[DocTreeGenerator]] and its `Convert-HelpToHtmlTree` function as the missing layer above `Get-Help`, generating cross-linked HTML documentation for modules and namespaces. The article treats module manifests, overview pages, templates, and structural conventions as part of documentation architecture rather than cosmetic extras.

## Key Claims
- `Get-Help` is useful but insufficient when users need a complete API-level documentation tree.
- [[DocTreeGenerator]] can generate browsable HTML documentation from documented modules with relatively little extra metadata.
- Good documentation structure depends on manifests, overview files, and consistent module organization.

## Key Quotes
> "documenting individual methods or classes or files is not the same as documenting an API"

## Connections
- [[MichaelSorens]] — author of the documentation workflow.
- [[DocTreeGenerator]] — the module used to generate HTML documentation trees.
- [[PowerShellDocumentation]] — the broader concept this article strengthens.
- [[ScriptArchitecture]] — documentation structure is tied to module and namespace layout.

## Contradictions
- No direct contradictions with current wiki content.
