---
title: "Beyond custom objects: Create a .NET class"
type: source
tags: [powershell, classes]
date: 2026-04-08
source_file: raw/PowerShell/Classes/Beyond custom objects Create a .NET class.md
---

## Summary
This source captures guidance and examples for beyond custom objects: create a .net class in a PowerShell context. It expands the wiki's classes coverage with operational patterns, commands, and implementation notes.

## Key Claims
- **OutputType**. Enclose in square brackets the .NET type of the objects that the method returns. If the method doesn't return anything, that is, if the output type is **\[Void\]**, you can omit the output type, because Void is the default. It's nice to include it anyway.Unlike the output types of functions, which are just notes, the output types of methods are enforced. If the method doesn't return the declared output type, the method generates an error
- **Name**. Specify the name of the method. Typically, method names are a single camel-cased string
- **Parameters**. The parameters of a method are always mandatory and positional. Each method has only one parameter set. Methods in a class can have the same name as other methods, but if they do, they must take different types and numbers of parameters. The parentheses that surround the parameters are required, even when the method doesn't take any parameters

## Key Quotes
> "https://www.sapien.com/blog/2014/12/02/beyond-custom-objects-create-a-net-class/" — source text

## Connections
- [[PowerShell]] — execution and scripting foundation
- [[PowerShellClasses]] — primary domain entity in this source set
- [[ObjectOrientedPowerShell]] — recurring concept reinforced by this source

## Contradictions
- No direct contradiction detected with current wiki pages.
