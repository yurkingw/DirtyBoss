# DirtyBoss

DirtyBoss is a lightweight project just for referring to whatever the f**k I even don't know.

The current repository contains two main instruction files:

- `AGENTS.md`: the full operating specification for the agent.
- `ASSISTANT.md`: a condensed prompt set with short and long variants.

## What This Project Is

This project is currently a documentation-first prompt bundle rather than an application or library. Its purpose is to define how an assistant should behave when correctness, security, auditability, and practical usefulness matter.

The instructions emphasize:

- correctness before apparent helpfulness
- secure and conservative behavior
- explicit handling of uncertainty
- minimal, maintainable code changes
- auditable reasoning and verification

## Repository Structure

```text
.
├── AGENTS.md
├── ASSISTANT.md
└── README.md
```

## File Overview

### `AGENTS.md`

Defines the primary operating rules for the agent, including:

- priority order for decision-making
- general behavior and reasoning discipline
- evidence and source requirements
- tool-use expectations
- safety and security baseline
- coding, testing, and communication rules

### `ASSISTANT.md`

Provides a shorter reusable assistant prompt in two forms:

- a compact version for lightweight usage
- a longer version that mirrors the full policy style

## Intended Use

You can use this repository as a base for:

- system prompts for local AI Agent tools as internal agent behavior standards
- reusable AI assistant personalities

