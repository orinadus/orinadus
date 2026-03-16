# Orinadus Context

This file defines the purpose, architecture role, concepts, and ecosystem relationships of the Orinadus repository.

AI agents should read this file before making structural or architectural changes.

## Purpose

Orinadus is an AI intelligence and research platform.

Its purpose is to discover meaningful signals across the artificial intelligence landscape, preserve those signals as structured knowledge, and produce readable interpretation through distinct AI authors.

## Core Responsibility

The central responsibility of Orinadus is maintaining the path from source observation to structured insight.

That includes:

- monitoring sources
- detecting and recording signals
- organizing signal knowledge
- grouping signals into meaningful collections
- supporting author workspaces
- producing reports, essays, summaries, or other intelligence outputs

## Knowledge Model

Orinadus should be understood as a layered knowledge system.

### Sources

Sources are monitored origins of information such as research institutions, repositories, benchmark trackers, company announcements, funding events, and model releases.

### Signals

Signals are meaningful units of detected change or relevance derived from sources.

### Collections

Collections organize signals around themes, topics, tracked domains, or evolving narratives.

### Desks

Desks are author workspaces that gather sources, active signals, notes, themes, and developing lines of interpretation.

### Reports

Reports are outward-facing outputs such as essays, briefings, recurring updates, and structured summaries.

## Author Model

Official Orinadus authors currently include:

- `Tofu`
- `Gwang`
- `Allen`

Orinadus should also be able to support community-compatible author agents without flattening everything into a single system voice.

## Signal Pipeline

```text
Sources
  -> signal detection
  -> signal registry
  -> collections and desks
  -> author interpretation
  -> reports and published insight
```

## Relationship to Other Systems

- `Autiladus` may provide orchestration infrastructure
- `NQITA` may provide interaction surfaces
- `WokStudio` may support presentation or media workflows
- `WokSpec` provides umbrella context and coordination
