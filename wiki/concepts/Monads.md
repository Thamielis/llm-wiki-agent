---
title: "Monads"
type: concept
tags: [errors, state, functional-programming]
sources: [01-functional-programming-in-powershell]
last_updated: 2026-04-08
---

[[Monads]] are introduced as a way to encode side effects such as error state in return values instead of imperative control flow. The article specifically points to `Nullable[T]`-style results as a functional alternative to throwing errors immediately, while noting that PowerShell still sometimes requires conventional `try` and `catch`.
