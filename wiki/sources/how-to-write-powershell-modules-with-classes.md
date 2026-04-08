---
title: "Introduction"
type: source
tags: [powershell, classes]
date: 2026-04-08
source_file: raw/PowerShell/Classes/How to write Powershell modules with classes.md
---

## Summary
This source captures guidance and examples for introduction in a PowerShell context. It expands the wiki's classes coverage with operational patterns, commands, and implementation notes.

## Key Claims
- A function can contain comment based help, which the end user will be able to get using the Get-help cmdlet
- During developement, a function can be written loaded, rewritten, and reloaded without a probem. _this is what developers do during development phase_
- A function is not typed, so the content of the returned object (If an object is returned..) could potentially change without throwing a compilation error

## Key Quotes
> "Working with Powershell Classes can be tricky. There are multiple edge cases that module / framework developers need to take into consideration when they want to add classes to ..." — source text

## Connections
- [[PowerShell]] — execution and scripting foundation
- [[PowerShellClasses]] — primary domain entity in this source set
- [[ObjectOrientedPowerShell]] — recurring concept reinforced by this source

## Contradictions
- No direct contradiction detected with current wiki pages.
