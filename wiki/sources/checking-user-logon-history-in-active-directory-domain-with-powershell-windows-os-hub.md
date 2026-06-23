---
title: "Checking User Logon History in Active Directory Domain with PowerShell  Windows OS Hub"
type: source
tags: [powershell, active-directory, auditing]
sources: [checking-user-logon-history-in-active-directory-domain-with-powershell-windows-os-hub]
last_updated: 2026-04-08
date: 2026-04-08
source_file: raw/PowerShell/woshub/Checking User Logon History in Active Directory Domain with PowerShell  Windows OS Hub.md
---

## Summary
Guide for reconstructing AD user logon activity from domain controller security logs using PowerShell. It covers audit policy prerequisites and event-based extraction via Event IDs 4624 and 4768 across multiple domain controllers.

## Key Claims
- Accurate user logon history requires auditing policy enablement on DCs.
- Event IDs 4624 and 4768 provide complementary visibility into authentication activity.
- Querying all DCs is necessary for complete domain-wide history.

## Key Quotes
> "you may want to view the history of user activity (logons) in a domain"

## Connections
- [[ADAdministration]] — domain authentication/audit operations.
- [[WindowsTroubleshooting]] — event-driven troubleshooting and investigation.
- [[PowerShell]] — log extraction tooling.

## Contradictions
- None identified.
