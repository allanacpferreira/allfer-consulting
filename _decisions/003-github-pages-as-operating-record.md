---
title: "GitHub Pages as Operating Record and Chairman Visibility System"
date: 2026-06-01
status: Decided
status_color: green
author: Founding Team
context: "The company needed a reporting system for the Chairman and a public-facing presence. The question was whether to build these separately or as a single system."
outcome: "Single Jekyll/GitHub Pages site serves both purposes — public marketing and Chairman operating record. Internal pages (Dashboard, Decision Log, Research, Risk Register, Prompt Log) are openly accessible but not actively promoted to clients."
---

## The Decision

One site. One codebase. The public-facing pages (Home, Services, Capabilities, Case Studies, Contact) serve as the marketing site. The operating record pages (Dashboard, Decisions, Research, Risks, Prompts, IP Roadmap) serve as the Chairman visibility system.

## Why One System

- Reduces maintenance overhead (one deployment, one update cycle)
- Transparency is a positioning signal — showing the decision log and research process demonstrates rigor to clients who discover it
- The operating record is not sensitive; it documents strategic thinking, not financials or client data
- Jekyll collections make it easy to add entries to each log without modifying layout files

## Tradeoffs Accepted

- Operating record pages are not hidden — any visitor can read the decision log or risk register
- This requires the team to write clearly and professionally in all operating record entries, not just in marketing content
- If client-sensitive information needs to be logged in future, it will require a separate private system

## Site Architecture

| Section | Purpose | Audience |
|---|---|---|
| Home, Services, Capabilities, Case Studies, Contact | Marketing | Prospective clients |
| Dashboard | Company scorecard | Chairman primary, clients secondary |
| Decisions, Research, Risks, Prompts, IP | Operating record | Chairman primary |

## Review Point

If any client or engagement data needs to be documented that cannot be made public, a private document system will be created. The public site will never contain confidential client information.
