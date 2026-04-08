---
title: "Immutability"
type: "concept"
tags: [state, debugging, reliability]
sources: [01-functional-programming-in-powershell]
last_updated: "2026-04-08"
---

[[Immutability]] means avoiding in-place mutation and preferring copy-on-write behavior when changes are needed. In the current wiki, it matters because reduced shared state leads to easier debugging, cleaner reasoning, and more reliable reruns.
