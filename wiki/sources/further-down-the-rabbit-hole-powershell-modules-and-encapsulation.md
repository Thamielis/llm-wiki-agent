---
title: "Further Down the Rabbit Hole: PowerShell Modules and Encapsulation"
type: "source"
tags: [powershell, modules, encapsulation]
sources: [further-down-the-rabbit-hole-powershell-modules-and-encapsulation]
last_updated: "2026-04-08"
date: "2026-04-08"
source_file: "raw/PowerShell/01_Development/Documenting/Further Down the Rabbit Hole PowerShell Modules and Encapsulation.md"
---

## Summary
Michael Sorens uses modules as the natural endpoint of a progression from inline code to functions to files to packaged reusable components. The article frames modules as a practical answer to scope pollution, hidden dependencies, naming collisions, and poor reuse. It also collects design guidance around manifests, exports, approved verbs, documentation, and robustness.

## Key Claims
- Encapsulation in PowerShell becomes materially stronger once code is moved into modules.
- Dot-sourcing and loose file organization are workable but scale poorly because they leak implementation details into shared scope.
- Good module design depends on explicit exports, naming discipline, manifests, and documentation.

## Key Quotes
> "The first half of this article guides you along the twisted path from raw code to tidy module"

## Connections
- [[MichaelSorens]] — author guiding the transition from scripts to modules.
- [[PowerShellModules]] — the primary concept the article develops.
- [[Encapsulation]] — the design principle used to justify module boundaries.
- [[CommentBasedHelp]] — part of the module design best-practices discussion.

## Contradictions
- No direct contradictions with current wiki content.
