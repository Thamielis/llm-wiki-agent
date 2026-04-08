---
title: "Formatting Objects without XML"
type: "source"
tags: [powershell, formatting, ps1xml]
sources: [formatting-objects-without-xml]
last_updated: "2026-04-08"
date: "2026-04-07"
source_file: "raw/PowerShell/01_Development/Formatting Objects without XML.md"
---

## Summary
Patrick Meinecke shows that PowerShell formatting metadata can be built through `PSControl` classes and builder objects rather than handwritten XML. The article demonstrates how `TableControl`, `CustomControl`, `ExtendedTypeDefinition`, and `FormatViewDefinition` can be composed programmatically and then exported or loaded into a session. The broader point is that PowerShell formatting is more discoverable and scriptable than many users assume.

## Key Claims
- PowerShell custom formatting can be built through .NET formatting classes instead of directly authoring ps1xml by hand.
- The builder APIs expose the same formatting concepts in a more discoverable, script-friendly form.
- Complex custom views can be used not only for display but also for code-generation-like output scenarios.

## Key Quotes
> "The bad news is, what I’m about to tell you is still going to involve XML. The good news, you don’t have to write it."

## Connections
- [[PatrickMeinecke]] — author explaining formatting builders.
- [[PowerShell]] — the language and runtime exposing the formatting APIs.
- [[PowerShellFormatting]] — the main concept explored in the article.
- [[ObjectIntrospection]] — related because both articles help users understand or present complex objects.

## Contradictions
- No direct contradictions with current wiki content.
