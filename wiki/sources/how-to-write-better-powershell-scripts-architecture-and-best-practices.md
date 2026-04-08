---
title: "How to Write Better PowerShell Scripts: Architecture and Best Practices"
type: "source"
tags: [powershell, best-practices, architecture]
sources: [how-to-write-better-powershell-scripts-architecture-and-best-practices]
last_updated: "2026-04-08"
date: "2025-08-29"
source_file: "raw/PowerShell/01_Development/How to Write Better PowerShell Scripts Architecture and Best Practices.md"
---

## Summary
Emanuele Bartolesi presents a broad PowerShell best-practices guide covering script and module structure, parameter validation, output and formatting, error handling, testing with Pester, and repository layout. The article is more general and checklist-oriented than the Kuech series, but it reinforces many of the same maintainability concerns around modularity, validation, and clear boundaries. It is a practical survey of common conventions rather than a single architectural thesis.

## Key Claims
- Good PowerShell scripts require attention to architecture, parameters, output, errors, and tests rather than just syntax.
- Parameters should be validated declaratively with standard attributes such as `ValidateSet`, `ValidateScript`, and related validators.
- Modules and scripts benefit from consistent structure, comment-based help, and explicit exports.
- Pester is the default testing framework for unit testing PowerShell code.

## Key Quotes
> "writing good PowerShell scripts requires more than just knowing the syntax and commands."

## Connections
- [[EmanueleBartolesi]] — author of the best-practices survey.
- [[PowerShell]] — the language being discussed.
- [[ScriptArchitecture]] — one of the major themes of the article.
- [[PowerShellModules]] — discussed as a primary unit of reuse and structure.
- [[PowerShellTesting]] — represented through the article's Pester guidance.
- [[PowerShellFormatting]] — touched on through its section on output formatting.

## Contradictions
- No direct contradictions with current wiki content; this source is broader and less opinionated than the Kuech series.
