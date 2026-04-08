---
title: "Invocation Operators, States and Scopes"
type: "source"
tags: [powershell, scope, session-state]
sources: [invocation-operators-states-and-scopes]
last_updated: "2026-04-08"
date: "2026-04-07"
source_file: "raw/PowerShell/01_Development/Invocation Operators, States and Scopes.md"
---

## Summary
Patrick Meinecke explains the `&` and `.` invocation operators by connecting them to PowerShell session state internals, module state, and scope creation. The article argues that many misconceptions about dot-sourcing and scope come from assuming a simple call-stack model instead of separate session-state trees for modules and top-level execution. It also highlights lesser-known uses of invoking `CommandInfo` and `PSModuleInfo` objects directly.

## Key Claims
- The semantics of `&` and `.` make more sense when understood in terms of execution context and session state rather than only call stack intuition.
- Module session state is distinct from top-level session state, which explains several confusing scoping behaviors.
- Dot-sourcing avoids creating a new scope, but it may still run within the current scope of a different session state.
- `PSModuleInfo` can be used as a vehicle for invoking code in module state or other assigned session states.

## Key Quotes
> "When you dot source something it runs in the scope that is marked as the current scope in the session state the command is from."

## Connections
- [[PatrickMeinecke]] — author of the scoping deep dive.
- [[PowerShell]] — the runtime being explained.
- [[InvocationOperators]] — the core topic of `&` and `.` invocation.
- [[SessionState]] — the internal model used to explain the behavior.
- [[ScriptBlocks]] — central because functions, scripts, and prompt input all eventually involve scriptblocks.

## Contradictions
- No direct contradictions with current wiki content.
