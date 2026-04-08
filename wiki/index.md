# Wiki Index

This file is maintained by the LLM. Updated on every ingest.

## Overview
- [Overview](overview.md) — living synthesis across all sources

## Sources
- [Functional Programming in PowerShell](sources/01-functional-programming-in-powershell.md) — pragmatic functional patterns in PowerShell through scriptblocks, pipelines, and side-effect minimization
- [Declarative DevOps](sources/02-declarative-devops.md) — desired-state DevOps as a cleaner and more idempotent alternative to imperative automation
- [DevOps Microframeworks](sources/03-devops-microframeworks.md) — why DevOps teams benefit from small, single-purpose internal frameworks
- [Private PowerShell Modules](sources/04-private-powershell-modules.md) — a git-first approach to packaging, referencing, and deploying PowerShell modules privately
- [Writing Maintainable PowerShell](sources/05-writing-maintainable-powershell.md) — using MVC-style separation and modules to keep large PowerShell codebases manageable
- [Declarative Config Management](sources/06-declarative-config-management.md) — cluster-set-based partial configuration merging for large non-homogeneous environments
- [Declarative Idempotency](sources/07-declarative-idempotency.md) — a requirement-driven engine for synchronous, validated, consistently logged idempotent automation
- [Automating Work-Item Management](sources/08-automating-work-item-management.md) — turning TODO comments into structured work items with PowerShell regex and pipeline transforms
- [Declarative DevOps Microframeworks Series Overview](sources/declarative-devops-microframeworks-series-overview.md) — landing page that organizes the series into concepts and applied walkthroughs
- [Display-Object: a PowerShell utility Cmdlet](sources/display-object-a-powershell-utility-cmdlet.md) — recursive object-path introspection for exploring nested PowerShell values
- [Formatting Objects without XML](sources/formatting-objects-without-xml.md) — using PowerShell formatting classes and builders instead of handwritten ps1xml
- [Functional Programming in PowerShell - The Startup Version](sources/functional-programming-in-powershell-the-startup-version.md) — alternate markdown capture of the same functional-programming article with fuller inline examples
- [Functional Programming in PowerShell - Original Markdown Version](sources/functional-programming-in-powershell-original-markdown-version.md) — another markdown capture of the same functional-programming article, preserved for provenance
- [How to Write Better PowerShell Scripts: Architecture and Best Practices](sources/how-to-write-better-powershell-scripts-architecture-and-best-practices.md) — general best-practice guidance for script architecture, parameters, output, errors, and testing
- [Invocation Operators, States and Scopes](sources/invocation-operators-states-and-scopes.md) — deep dive into invocation operators, session state, module scope, and dot-sourcing behavior
- [Top 20 PowerShell Modul- und Skriptvorlagen](sources/top-20-powershell-modul-und-skriptvorlagen.md) — German roundup of PowerShell module and script templates with pros and cons

## Entities
- [Christopher Kuech](entities/ChristopherKuech.md) — author of the series-heavy PowerShell architecture corpus
- [PowerShell](entities/PowerShell.md) — host language for the wiki's current automation, internals, and formatting patterns
- [Declarative DevOps Microframeworks](entities/DeclarativeDevOpsMicroframeworks.md) — the umbrella series tying many current sources together
- [ConfigSets](entities/ConfigSets.md) — module implementing cluster-set-based partial configuration selection
- [Requirements](entities/Requirements.md) — module implementing requirement-driven declarative idempotency
- [Phil Factor](entities/PhilFactor.md) — author of the Display-Object utility article
- [Patrick Meinecke](entities/PatrickMeinecke.md) — author covering formatting internals and session state
- [Emanuele Bartolesi](entities/EmanueleBartolesi.md) — author of the PowerShell best-practices survey

## Concepts
- [Functional Programming](concepts/FunctionalProgramming.md) — data-first, transformation-oriented PowerShell design
- [Higher-Order Functions](concepts/HigherOrderFunctions.md) — pipeline transforms that take behavior as input
- [ScriptBlocks](concepts/ScriptBlocks.md) — PowerShell first-class functions and closures
- [Immutability](concepts/Immutability.md) — copy-on-write discipline for reducing shared state
- [Monads](concepts/Monads.md) — return-value encoding of error state in functional flow
- [Declarative Programming](concepts/DeclarativeProgramming.md) — expressing desired outcomes instead of step-by-step mutation
- [Declarative DevOps](concepts/DeclarativeDevOps.md) — desired-state automation for operations work
- [DevOps Microframeworks](concepts/DevOpsMicroframeworks.md) — small reusable frameworks for recurring operational tasks
- [MVC](concepts/MVC.md) — model-view-controller adapted to PowerShell CLI design
- [PowerShell Modules](concepts/PowerShellModules.md) — packaging and interface boundaries for reusable automation
- [Configuration Management](concepts/ConfigurationManagement.md) — selecting and composing environment-specific configuration safely
- [Idempotency](concepts/Idempotency.md) — reliable reruns that converge to the same result
- [Desired State Configuration](concepts/DesiredStateConfiguration.md) — PowerShell DSC as built-in desired-state automation
- [Work-Item Automation](concepts/WorkItemAutomation.md) — turning code annotations into structured tasks
- [PowerShell Formatting](concepts/PowerShellFormatting.md) — presenting objects through built-in and custom views
- [Object Introspection](concepts/ObjectIntrospection.md) — exploring object shape and paths programmatically
- [Invocation Operators](concepts/InvocationOperators.md) — the semantics of `&` and `.` in relation to state
- [Session State](concepts/SessionState.md) — PowerShell runtime state tree for variables and scopes
- [Script Architecture](concepts/ScriptArchitecture.md) — file, module, and interface structure for maintainable scripts
- [PowerShell Testing](concepts/PowerShellTesting.md) — Pester and interface-oriented validation patterns
- [Module Templates](concepts/ModuleTemplates.md) — starter repositories and scaffolds for new PowerShell projects

## Syntheses
