---
title: Website
kind: project
created: 2026-06-30
---

# Website

This is the Markdown-native project memory entry point for Code Atlas.

:::git-status
:::

## Project Memory

Use this document to describe the project, current focus, important
files, and durable engineering knowledge.

## Important Files

Use structured references to connect project memory to code:

- [[file:README.md]]
- [[folder:.atlas]]

:::reference-health{scope="project"}
:::

:::context-packet{target="relay"}
:::

## Decisions

Embed lightweight decisions directly in this document:

:::decision{id="local-first-memory" status="proposed"}
# Keep Project Memory Local First

## Context
Code Atlas should preserve developer knowledge in readable project files.

## Decision
Use `.atlas/` Markdown documents as the source layer.

## Consequences
- Project memory stays local and versionable.
- Structured views can be derived from Markdown.
:::