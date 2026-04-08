---
title: "Immutability"
type: concept
tags: [state, debugging, reliability]
sources: [01-functional-programming-in-powershell]
last_updated: 2026-04-08
---

[[Immutability]] is described as avoiding in-place modification and instead cloning data before writes. In the PowerShell context, the article argues that this copy-on-write discipline reduces shared state, makes debugging easier, and pairs naturally with pure functions and idempotent scripts.
