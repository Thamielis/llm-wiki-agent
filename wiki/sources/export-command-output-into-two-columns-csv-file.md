---
title: "Export command output into two columns CSV file"
type: source
tags: [powershell, basics, csv]
date: 2026-06-23
source_file: raw/PowerShell/basics/Export command output into two columns CSV file.md
---

## Summary
This source shows how to reshape command output into a two-column CSV with `Property` and `Value` fields. It uses a `DataTable`, iterates through object properties, and flattens each property value into exportable rows.

## Key Claims
- Some command output is easier to work with when each property/value pair becomes its own CSV row
- `DataTable` and `DataColumn` can be used to build a two-column export structure
- `Out-String` helps normalize property values before they are inserted into the table
- The resulting table can be inspected in `Out-GridView` and exported with `Export-Csv`

## Key Quotes
> "I just wanted to create CSV file with two columns." — source text

## Connections
- [[PowerShellFormatting]] — reshapes object output into a tabular export format
- [[ObjectIntrospection]] — walks object properties programmatically
- [[PowerShellBasics]] — common data-shaping pattern for admin scripting

## Contradictions
- No direct contradiction detected with current wiki pages.
