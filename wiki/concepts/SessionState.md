---
title: "Session State"
type: "concept"
tags: [powershell, scope, runtime]
sources: [invocation-operators-states-and-scopes]
last_updated: "2026-04-08"
---

[[SessionState]] is the PowerShell runtime model that tracks variables, scopes, and module-specific execution state. In the current wiki it is the key to understanding dot-sourcing, module scope behavior, and why PowerShell scope rules often differ from naive call-stack expectations.
