---
title: "Automate Jira ↔ GitHub with Codex"
type: source
tags: [openai, jira, github, automation, codex]
date: 2025-08-26
source_file: raw/PowerShell/01_Development/GitHub-Actions/Automate Jira ↔ GitHub with Codex.md
---

## Summary
This cookbook article shows how to wire Jira automation to GitHub Actions so a labeled issue can trigger Codex to implement a change, open a pull request, and post status updates back to Jira. It is a concrete workflow example of using Codex as an agentic step inside a larger issue-to-PR pipeline.

## Key Claims
- A Jira label can be used as the trigger that dispatches a GitHub Actions workflow
- Codex can run inside the GitHub Action, make the code change, and commit it automatically
- The workflow can update Jira status and add the PR link back to the ticket

## Key Quotes
> "This setup allows teams to tightly control which Jira issues trigger automation" — source text

## Connections
- [[Jira]] — the source system that triggers and receives workflow updates
- [[GitHubActions]] — the automation runtime that runs the Codex step
- [[Codex]] — the agent used to implement the change inside the workflow
- [[AIWorkflowAutomation]] — the broader concept represented by this cookbook

## Contradictions
- No direct contradiction detected with current wiki pages.
