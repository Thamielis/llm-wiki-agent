---
title: "Private PowerShell Modules"
type: "source"
tags: [powershell, modules, packaging]
sources: [04-private-powershell-modules]
last_updated: "2026-04-08"
date: "2025-05-20"
source_file: "raw/PowerShell/01_Development/04_Private PowerShell Modules.md"
---

## Summary
This guide argues that PowerShell modules are the best packaging format for private DevOps microframeworks because they are modular, portable, and easy to copy into deployment environments. Instead of standing up a private gallery, Kuech recommends storing modules in git and distributing them as files at deployment time. The article walks through a minimal module structure, manifest choices, `PSModulePath` usage, and deployment considerations.

## Key Claims
- Private PowerShell modules are simpler to develop and distribute from git than from private gallery infrastructure.
- A minimal module should include a manifest, module script, tests, README, and `.gitignore`.
- Modules should be referenced by name rather than by path to avoid unnecessary coupling to filesystem layout.
- Deploying a module privately is usually just a matter of copying the module folder into a target module path.
- Manifest metadata such as exported functions and required modules defines the module's public interface and dependencies.

## Key Quotes
> "by far the simplest and easiest way to develop and release your module for private consumption is to store them in `git` and copy the files at deployment time."

## Connections
- [[ChristopherKuech]] — author of the packaging guidance.
- [[DeclarativeDevOpsMicroframeworks]] — the series context in which modules become reusable DevOps building blocks.
- [[PowerShell]] — the module system being used for packaging and reuse.
- [[PowerShellModules]] — the main packaging pattern promoted by the article.
- [[DevOpsMicroframeworks]] — modules are presented as the ideal delivery vehicle for these internal frameworks.

## Contradictions
- No direct contradictions with current wiki content.
