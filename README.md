# MMS-AI

> A living strategy built across 6 sessions. Each module adds one component. By Module 6, this repo IS the strategy, version-controlled, board-ready, portable.

---

## Strategy at a Glance

| Component | Module | Status | Key Artifact |
|-----------|--------|--------|-------------|
| **The Bet** | M1 | [x] | `01-the-bet/` |
| **The Moat** | M2 | [x] | `02-the-moat/` |
| **The Margin** | M3 | [x] | `03-the-margin/` |
| **The Contract** | M4 | [x] | `04-the-contract/` |
| **The Guardrails** | M5 | [x] | `05-the-guardrails/` |
| **The Pitch** | M6 | [x] | `06-the-pitch/` |

---

## The Bet (M1)

**What we're building, for whom, why now.**

- **Product:** MMS-AI (Maintenance Assistant/Co-pilot) is a chat interface add-on that help with maintenance scheduling, operator support during troubleshooting.
- **AI Value Archetype:** Copilot
- **Vulnerability Scores:** _(add: Moat 3/5 · Data 4/5 · Platform 4/5)_
- **Top Risk:** Entrenched vertical competitor could offer similar product in 6 months
- **Confidence:** M
- **Prototype:** https://claude.ai/code/artifact/a85067a6-6531-4d40-876c-62e8d6d9dc98
- **Kill Criteria:** *If at least 25% users at deployed factories do not use the troubleshooting function at least once in 3 months*

→ Details: [`01-the-bet/`](01-the-bet/)

---

## The Moat (M2)

**Why this won't get copied in 6 months.**

- **Data Flywheel Score:** 9/20
- **Weakest Loop:** *Domain Context Loop*
- **Top Encroachment Threat:** *OpenAI*
- **Encroachment Defense:** *since current functions do not have cross domain transfer opportunity, we should add new functionality that support cross domain transfer*
- **Vendor Portability:**  Partial 

→ Details: [`02-the-moat/`](02-the-moat/)

---

## The Margin (M3)

**Will this make money or bleed it?**

- **Gross Margin (current):** $5
- **Gross Margin (AI-adjusted):** 
- **Pricing Model:** outcome-based
- **Pricing Today → Tomorrow:** N/A → *Strategy posture:* Penetrate
- **Total AI COGS / unit:** $18
- **Cascading Strategy:** Triage: Haiku 4.5; frontier: Sonnet 5.0; ratio 70%
- **Net Margin Shift:** 
- **Break-even at:** $30

→ Details: [`03-the-margin/`](03-the-margin/)

---

## The Contract (M4)

**Why users will trust a probabilistic system.**

- **Reliability Target:** 90%
- **Golden Dataset:** Total: 6, Edge cases: 2 (33.3%), Judge mix: 33% rule / 33% LLM / 33% both
- **Confidence UX:** show uncertainty / tiered confidence
- **HITL Architecture:** **Trigger:** At a fixed interval (1/week)
- **Failure Mode Coverage:** *What failure mode did your partner find that you missed?*

→ Details: [`04-the-contract/`](04-the-contract/)

---

## The Guardrails (M5)

**What breaks when this scales, and what compounds.**

- **Compounding System:** | Loop | Input | Output | Compounds? | Status | |------|-------|--------|-----------|--------| | Recursive Learning | User corrects/rejects troubleshooting guidance | updated runbook for AI | Y | active | | Cross-Domain …
- **Governance Posture:** AI features in the maintenance copilot troubleshooting guidance and schedule optimization functions Excludes: General maintenance functions not supported by the copilot
- **Autonomy Boundaries:** Fixing issues, never auto. Applying schedule optimzation, human approval required. Troubleshooting guidance, auto.
- **Escalation Triggers:** 1. Multiple attempts are troubleshooting failed and production line is now down 2. Applying schedule optimization messes up the schedule
- **Audit Cadence:** Monthly, Test readiness for switching verdors (PM). Weekly, Automated smoke test against golden dataset (Devops). Real-time, SRE level monitoring.
- **Shadow AI Audit (user-side):** __ workarounds found · **Estimated hidden spend:** build candidates
- **Agent Boundaries:** N/A
- **Regulatory Exposure:** SOC 2. Risk tier: limited. Controls: maintain audit log of suggestions from the copilot as well as.

→ Details: [`05-the-guardrails/`](05-the-guardrails/)

---

## The Pitch (M6)

**How you get this funded, shipped, and adopted.**

- **Horizon 1 (Now):**
- **Horizon 2 (Next):**
- **Horizon 3 (Bet):**
- **Board Narrative:** **The case:**
- **Ask:** ## M1 Baseline vs. Now
- **Key Strategic Change:**

→ Details: [`06-the-pitch/`](06-the-pitch/)
