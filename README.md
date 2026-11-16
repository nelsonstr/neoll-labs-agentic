# Neoll Labs AI — Enterprise Autonomous Platform Documentation

Welcome to the central documentation hub for **Neoll Labs AI**, an autonomous software factory and multi-agent operations platform built on **Hermes Agent** (Native Kanban + Git Worktrees), **Vercel Infrastructure** (Team scope: `neoll-labs-projects`), **Supabase** (1 dedicated DB per app), and **Telegram Community Governance** (`Neoll-Labs.tlg`).

---

## Architecture Overview

```text
┌─────────────────────────────────────────────────────────────┐
│                 NEOLL LABS TECH HOLDINGS                    │
│                 Founder & Group CTO: Nelson Lourenço        │
└──────────────┬──────────────────────────────┬───────────────┘
               │                              │
               ▼                              ▼
    ┌────────────────────┐         ┌────────────────────┐
    │  HERMES NATIVE     │         │  VERCEL DUAL-TIER  │
    │  KANBAN & WORKFLOWS│         │  INFRASTRUCTURE    │
    │  • Task Routing    │         │  • Staging Preview │
    │  • Git Worktrees   │         │  • Production      │
    │  • Subagent Squads │         │  • <app>.neoll-labs│
    └──────────┬─────────┘         └──────────┬─────────┘
               │                              │
               └──────────────┬───────────────┘
                              │
                              ▼
    ┌─────────────────────────────────────────────────────────┐
    │            TELEGRAM COMMUNITY (Neoll-Labs.tlg)          │
    │  • Topic #1:  Geral / HQ                                │
    │  • Topic #55: Eco Swimming Pool                         │
    │  • Topic #58: Tertul-IA                                 │
    │  • Topic #62: Chat2App & ExpatHousing                   │
    └─────────────────────────────────────────────────────────┘
```

---

## Core Platform Components

### 1. Hermes Native Orchestration
- **Task Management**: Fully native Hermes Kanban (`kanban.db`) and automated subagent delegation.
- **Git Worktrees**: Isolated worktrees under `C:\Users\ai\ao\projects\<app>` for each venture branch.
- **Ventures**:
  - `neoll-holding`: Parent holding company aggregating all IT & AI ventures.
  - `chat2app`: Chat-driven autonomous app factory & AI agents.
  - `eco-swimming-pool`: Sustainable pool tech e-commerce & CFD design.
  - `expat-housing-pt`: Foreigner real estate PropTech & lead qualification.
  - `tertul-ia`: AI intellectual salons and community hub.

### 2. Infrastructure Standard (Supabase + Vercel)
- **Database**: Exactly **1 dedicated Supabase project** per application under `neoll-labs-projects` org.
- **Hosting**: Vercel deployments under team scope `neoll-labs-projects` with subdomains under `neoll-labs.com`.
- **Staging Pipeline**: Staging branch (`<app>.staging.neoll-labs.com`) includes client chat banner and inline button sign-offs.

### 3. Client Onboarding Flow
1. **Intake & Topic**: Create private Telegram forum topic in `Neoll-Labs.tlg` and link bot credentials.
2. **Project Init**: Initialize project repository and Hermes Kanban board.
3. **Infrastructure**: Provision dedicated Supabase DB and Vercel project (`neoll-labs-projects`).
4. **Staging Preview**: Deploy to `<app>.staging.neoll-labs.com` with client review banner.
5. **Sign-off**: Client/Sales explicit Telegram button approval promotes to production (`<app>.neoll-labs.com`).
