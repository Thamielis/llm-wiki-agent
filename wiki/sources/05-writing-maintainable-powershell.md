---
title: "Writing Maintainable PowerShell"
type: "source"
tags: [powershell, architecture, maintainability]
sources: [05-writing-maintainable-powershell]
last_updated: "2026-04-08"
date: "2025-05-20"
source_file: "raw/PowerShell/01_Development/05_Writing Maintainable PowerShell.md"
---

## Summary
Kuech argues that large PowerShell codebases degrade when user-facing command surfaces and internal business logic blur together. He adapts MVC ideas to PowerShell by treating classes as models, exported cmdlets as views, and plain functions as controllers, with modules enforcing interface boundaries. The overall goal is to make scripts more testable, more portable, and easier to evolve into reusable microframeworks.

## Key Claims
- Large PowerShell codebases benefit from separating presentation logic, business logic, and data models.
- PowerShell classes are a good fit for models because they group state and model-specific behavior cleanly.
- Exported cmdlets should serve as views, while internal functions should act as controllers with simpler interfaces.
- Modules improve maintainability by enforcing interfaces, portability, and easier testing compared with loose scripts.
- Validation should happen at the view layer so controllers can remain simpler and cheaper to test.

## Key Quotes
> "Just like graphical user interfaces, command-line interfaces can benefit from this same separation."

## Connections
- [[ChristopherKuech]] — author translating common software architecture patterns into PowerShell terms.
- [[PowerShell]] — the language whose maintainability conventions are being shaped.
- [[DeclarativeDevOpsMicroframeworks]] — the series context for scaling PowerShell codebases.
- [[MVC]] — the architectural pattern adapted to command-line PowerShell.
- [[PowerShellModules]] — the packaging and boundary mechanism used to keep code manageable.
- [[DevOpsMicroframeworks]] — maintainability improvements are framed as a path toward smaller reusable frameworks.
- [[FunctionalProgramming]] — data views are explicitly encouraged to stay functional and side-effect free where possible.

## Contradictions
- No direct contradictions with current wiki content.
