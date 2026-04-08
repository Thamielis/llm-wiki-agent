# Wiki Index

This file is maintained by the LLM. Updated on every ingest.

## Overview
- [Overview](overview.md) — living synthesis across all sources

## Sources
- [Development Index](sources/development-index.md) — table of contents for the PowerShell development corpus and its documenting/tooling subsections
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
- [Documenting Your PowerShell Binary Cmdlets](sources/documenting-your-powershell-binary-cmdlets.md) — documenting C# cmdlets through XmlDoc2CmdletDoc instead of hand-authored MAML
- [Further Down the Rabbit Hole: PowerShell Modules and Encapsulation](sources/further-down-the-rabbit-hole-powershell-modules-and-encapsulation.md) — why modules are PowerShell's practical route to encapsulation and safer reuse
- [How To Document Your PowerShell Library](sources/how-to-document-your-powershell-library.md) — generating browsable HTML API documentation trees above standard Get-Help
- [PowerShell-Docs Style Guide](sources/powershell-docs-style-guide.md) — official conventions for syntax, examples, and PlatyPS-backed cmdlet reference articles
- [The PowerShell Script Orchestrator](sources/the-powershell-script-orchestrator.md) — PowerShell as a workflow glue layer across web APIs and external services
- [Towards the Perfect Build](sources/towards-the-perfect-build.md) — PowerShell-driven build, deployment, smoke-test, and bootstrap automation
- [Unified Approach to Generating Documentation for PowerShell Cmdlets](sources/unified-approach-to-generating-documentation-for-powershell-cmdlets.md) — wallchart synthesis tying cmdlet help generation to browsable API docs
- [Using C to Create PowerShell Cmdlets: The Basics](sources/using-c-to-create-powershell-cmdlets-the-basics.md) — step-by-step recipe for native-feeling C# cmdlets in PowerShell
- [Automate Jira and GitHub with Codex](sources/automate-jira-and-github-with-codex.md) — cookbook workflow for label-triggered Jira-to-PR automation through GitHub Actions and Codex

## Entities
- [Christopher Kuech](entities/ChristopherKuech.md) — author of the series-heavy PowerShell architecture corpus
- [PowerShell](entities/PowerShell.md) — host language for the wiki's automation, internals, documentation, and delivery-engineering patterns
- [Declarative DevOps Microframeworks](entities/DeclarativeDevOpsMicroframeworks.md) — the umbrella series tying many current sources together
- [ConfigSets](entities/ConfigSets.md) — module implementing cluster-set-based partial configuration selection
- [Requirements](entities/Requirements.md) — module implementing requirement-driven declarative idempotency
- [Phil Factor](entities/PhilFactor.md) — author of the Display-Object utility article
- [Patrick Meinecke](entities/PatrickMeinecke.md) — author covering formatting internals and session state
- [Emanuele Bartolesi](entities/EmanueleBartolesi.md) — author of the PowerShell best-practices survey
- [Michael Sorens](entities/MichaelSorens.md) — author focused on PowerShell modules, binary cmdlets, and documentation workflows
- [Adam Bertram](entities/AdamBertram.md) — author presenting PowerShell as a cross-service orchestration language
- [Matt Wrock](entities/MattWrock.md) — author extending the corpus into CI, deployment automation, and bootstrap scripting
- [XmlDoc2CmdletDoc](entities/XmlDoc2CmdletDoc.md) — tool for generating PowerShell help artifacts from C# XML doc comments
- [DocTreeGenerator](entities/DocTreeGenerator.md) — tool for generating browsable HTML API trees from PowerShell help metadata
- [PlatyPS](entities/PlatyPS.md) — Markdown-based PowerShell documentation tooling with schema-enforced cmdlet reference structure
- [GitHub Actions](entities/GitHubActions.md) — workflow runtime used for the Jira-to-PR Codex automation example
- [Jira](entities/Jira.md) — issue-tracking system driving and receiving status from the automated workflow
- [Codex](entities/Codex.md) — coding agent embedded in the cookbook ticket-to-PR loop

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
- [PowerShell Testing](concepts/PowerShellTesting.md) — Pester, smoke tests, and validation patterns for maintainable automation
- [Module Templates](concepts/ModuleTemplates.md) — starter repositories and scaffolds for new PowerShell projects
- [PowerShell Documentation](concepts/PowerShellDocumentation.md) — help generation, doc structure, and standards for PowerShell libraries and cmdlets
- [Binary Cmdlets](concepts/BinaryCmdlets.md) — compiled PowerShell cmdlets implemented in C# or other .NET languages
- [Comment-Based Help](concepts/CommentBasedHelp.md) — inline PowerShell help content used by Get-Help and downstream tooling
- [Encapsulation](concepts/Encapsulation.md) — separating interface from implementation through functions and modules
- [Script Orchestration](concepts/ScriptOrchestration.md) — using PowerShell as a control layer across APIs and services
- [Build Automation](concepts/BuildAutomation.md) — scripted compilation, packaging, deployment, and release routines
- [Continuous Integration](concepts/ContinuousIntegration.md) — automated repository workflows for build, test, and delivery
- [Infrastructure Bootstrap](concepts/InfrastructureBootstrap.md) — bringing a clean machine to a usable state through scripts
- [AI Workflow Automation](concepts/AIWorkflowAutomation.md) — embedding coding agents inside issue-tracking and CI workflows

## Syntheses
