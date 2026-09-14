# OPD Attendance & Governance System (AppSheet)

An operational system I designed after taking responsibility for outpatient clinic administration in September 2025. I analyzed recurring attendance, scheduling, replacement, accountability, and governance problems and translated them into a structured AppSheet system with explicit rules and auditable data flows.

The system was **implemented and tested operationally with the outpatient team**, where the proposed workflow was well received. Full deployment was ultimately blocked by the hospital administration's decision not to fund the required AppSheet subscription.

This project demonstrates how I approached a real operational problem from a **data and systems perspective** while working in a medical environment.

## What the System Addresses

- Doctor attendance and daily operational status
- OFF scheduling and capacity-aware replacements
- Administrative status changes with audit history
- Behavioral/operational cases kept separate from attendance facts
- Role-based accountability and controlled writes
- Performance metrics derived from operational records
- Explicit business rules to prevent invalid actions

## Design Principles

- Data integrity over convenience
- Auditability over speed
- Explicit rules over informal judgment
- Clear ownership of operational data
- Historical records preserved rather than silently overwritten

## Repository Scope

This repository contains:

- System architecture and data semantics
- Business and operational rules with AppSheet expressions
- Design decisions and their rationale
- Operational rollout guidance

It intentionally contains **no patient data, real staff identifiers, hospital-specific confidential information, or production exports**.

## Navigation

- `docs/ARCHITECTURE.md` — system design and data model
- `docs/RULES.md` — business rules and AppSheet expressions
- `docs/DECISION_LOG.md` — key design decisions
- `docs/OPERATIONS.md` — operational workflow and safeguards
- `docs/ROADMAP.md` — future improvements

## Status

**Operationally implemented and evaluated; full institutional deployment was blocked by subscription funding.**

## License

MIT License
