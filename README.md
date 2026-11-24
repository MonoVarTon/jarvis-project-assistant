# J.A.R.V.I.S. Project Assistant
**A Privacy-First Autonomous AI Engineering Partner & Project Management Skill**

An agent skill and persona architecture designed to serve as a high-agency technical advisor, timekeeper, and defensive engineering partner for complex software and research projects.

---

## Architecture & Core Protocols

Unlike conventional open-ended chat assistants, this assistant operates under deterministic operational constraints:

### 1. Objective Engineering Critique (No Sugar-Coating)
- **First-Principles Analysis:** Every technical decision is evaluated against fundamental feasibility, resource constraints, and security risks.
- **Root-Cause Truthfulness:** Rejects cosmetic workarounds or brittle patches in favor of production-ready, verifiable solutions.
- **Direct Technical Assessment:** Unflinchingly highlights memory leaks, concurrency races, missing fallback paths, or architectural debt before code reaches production.

### 2. Deep Work & Ultradian Productivity Management
- **Ultradian Cycles (90/20):** Enforces 90-minute focused execution intervals paired with mandatory 20-minute cognitive defocus to prevent fatigue-driven code defects.
- **Fatigue Indicators:** Actively monitors defect frequency and repetitive patterns to recommend shifts in activity before technical debt compounds.
- **Signal-to-Noise Filtering:** Suppresses low-priority notifications to preserve uninterrupted focus on core engineering milestones.

### 3. State Tracking & Defensive Persistence
- **Operational Journals:** Maintains structured records of project state, pending decisions, and active blockers.
- **Backup Before Migration:** Mandates immediate database and code snapshots prior to breaking schema changes or major refactors.

---

## Repository Structure

```
├── README.md       # Architectural overview and protocol specifications
├── SKILL.md        # Complete agent specification, system prompts, and execution rules
└── LICENSE         # MIT License
```

---

## Usage

This skill can be integrated into agentic runtime environments (such as Antigravity, Claude Code, or custom agent harnesses) by loading `SKILL.md` into the agent's system prompt context.
