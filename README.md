# RogueReduxHub

Local-first companion platform for structured game-data extraction, read-only save inspection, and constraint-aware build analysis.

## Overview

RogueReduxHub is a TypeScript-first companion application focused on turning heterogeneous source material into a usable local product surface. The current implementation targets a complex ROM-hack ecosystem and combines:

- structured data extraction from archived source bundles
- normalized JSON generation and validation
- local search and wiki-style reference browsing
- read-only binary save metadata inspection
- deterministic recommendation logic constrained by parsed data
- mobile-first UI with desktop support for development and debugging

The product is intentionally local-first. Core workflows do not require a hosted backend.

## Technical Goals

- Build a reproducible data pipeline from raw archives into normalized app data
- Preserve provenance and confidence metadata throughout the stack
- Support read-only save analysis before any mutation-capable workflows
- Keep the recommendation layer deterministic and source-constrained
- Maintain a cross-platform path for web, desktop, and mobile packaging

## Current Stack

- React
- TypeScript
- Vite
- Zod
- Vitest
- Tauri v2 configuration
- Capacitor configuration

## Repository Focus

This repository is being used to document and direct the higher-fidelity product build. It currently stores:

- engineering-facing continuation prompts
- progress resume notes
- implementation status context for future agent passes

## Active Direction

The current design pass is centered on:

- mobile-first product UX
- premium dark UI treatment
- explicit confidence and provenance states
- short cinematic boot/loading motion
- operational surfaces for search, detail inspection, team analysis, and save review

Primary visual references currently in use:

- Factory.ai
- Biosphere77

## Constraints

- Local-first by default
- Read-only save handling
- No fabricated recommendation data
- No hidden uncertainty when source confidence is unresolved
- Raw copyrighted source inputs should remain outside versioned distribution artifacts

## Near-Term Work

- deepen the mobile design system
- add a polished cold-load animation
- continue fixture-backed save-structure research
- replace mock team flows with validated parsed-party data

## Status

This repository is currently a coordination and handoff hub for the main implementation thread rather than the primary application codebase itself.
