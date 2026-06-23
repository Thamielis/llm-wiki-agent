---
title: "How to modify the registry for all users with PowerShell - PDQ"
type: source
tags: [powershell, registry, configuration]
date: 2026-06-23
source_file: raw/PowerShell/basics/How to modify the registry for all users with PowerShell  PDQ.md
---

## Summary
This source describes how to apply a registry change in a way that affects all users instead of only the current session. It uses PowerShell's registry capabilities to reach the relevant hive or profile-backed location and automate the change consistently.

## Key Claims
- Registry automation can be aimed at a per-machine or all-users configuration surface
- The right hive or profile-backed location matters when changes must apply broadly
- PowerShell is well suited to repeatable registry updates that would be tedious manually
- This pattern is useful for configuration rollout and endpoint management

## Key Quotes
> "modify the registry for all users" — source title fragment

## Connections
- [[ConfigurationManagement]] — broad settings changes map to repeatable configuration rollout
- [[InfrastructureBootstrap]] — registry changes often support machine setup and hardening
- [[PowerShellBasics]] — the registry provider is a standard admin automation surface

## Contradictions
- No direct contradiction detected with current wiki pages.
