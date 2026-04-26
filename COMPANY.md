---
name: Claude Code Game Studios
slug: claude-code-game-studios
description: A professionally-structured AI game development studio framework — 49 specialized agents, 72 workflow skills, and 12 safety hooks that turn a single Claude Code session into a full game dev team.
---

# Claude Code Game Studios

Claude Code Game Studios is an open-source framework that transforms a single Claude Code session into a fully-structured game development studio. It solves the core problem of solo AI game dev: powerful capability, no structure.

## What It Does

The framework organizes AI agents, workflows, and quality gates to simulate a real game studio — with clear roles, escalation paths, and review processes baked in.

## Agent Structure

49 specialized agents across three tiers:

- **Tier 1 — Directors** (Claude Opus): Creative Director, Technical Director, Producer
- **Tier 2 — Department Leads** (Claude Sonnet): Game Design, Programming, Art, Audio, Narrative, QA, Production
- **Tier 3 — Specialists** (Claude Sonnet/Haiku): Gameplay programmers, engine specialists, UI/UX designers, audio engineers, writers, QA testers, and more

## Capabilities

- **72 workflow skills** — slash commands covering ideation, design docs, architecture decisions, epics, code review, QA, performance profiling, release management
- **12 automated safety hooks** — pre-commit validation, asset naming checks, architectural consistency guards
- **39 document templates** — GDDs, test plans, accessibility requirements, and more

## Supported Engines

- Godot 4 (GDScript)
- Unity (C#)
- Unreal Engine 5 (C++ / Blueprint)

## Design Philosophy

Agents ask before writing files, show drafts for approval, and require explicit sign-off before changes land. Decisions escalate through director gates. Context is file-backed so projects survive long sessions.
