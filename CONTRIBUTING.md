# Contributing to Orinadus

Orinadus is an AI author research platform — a place where autonomous research agents with distinct identities discover signals, organize knowledge, and produce structured interpretation. Building it well requires people with different skills and perspectives.

If the idea of authorial AI agents doing real research work interests you, there is likely a place for you here.

---

## What we're building

The platform is organized around a knowledge pipeline:

```
Sources → signal detection → signal registry → collections and desks → author interpretation → reports
```

Every part of that pipeline needs work. The current authors — Tofu, Gwang, and Allen — are in early development. The infrastructure that supports them is being built.

---

## Who we're looking for

### ML Engineers
Working on the models, prompting strategies, and agent architectures that give authors their reasoning capability. If you think carefully about how language models form interpretations — not just outputs — this is relevant work.

### Research Contributors
People who understand the AI landscape and can help define what good research looks like for each author. This includes defining source lists, signal taxonomies, and what rigorous authored analysis means in practice.

### Data Contributors
Helping build and curate the knowledge base that authors draw from — sources, structured signal records, historical context, domain-specific reference material.

### Platform Engineers
Building the infrastructure: signal pipelines, storage, author desk tooling, report generation, API surface. The platform has to work reliably for authors to work at all.

---

## How to get involved

1. Read [`ORINADUS_CONTEXT.md`](./ORINADUS_CONTEXT.md) to understand the architecture and philosophy
2. Browse the open issues — we tag issues with the relevant contributor type
3. Open an issue to propose something new or ask a question before starting significant work
4. Fork, branch, and submit a pull request with a clear description of what you changed and why

---

## Standards

- Keep changes scoped. Do one thing per pull request.
- If you're changing architecture or authorship model, open an issue for discussion first.
- AI agents operating in this repository should follow [`AGENT_RULES.md`](./AGENT_RULES.md).
- Be direct in code review. We value clarity over politeness.

---

## Questions

Open an issue. We will respond.
