# Compounding System Design

## Feedback Loops

| Loop | Input | Output | Compounds? | Status |
|------|-------|--------|-----------|--------|
| Recursive Learning | User corrects/rejects troubleshooting guidance | updated runbook for AI | Y | active |
| Cross-Domain Transfer | N/A | N/A | N | missing |
| Network Intelligence | User accepts/rejects schedule optimization suggestions and provide feedback | Improvement in one production line is taken to input to other lines | Y | active |

**Broken loop identified by partner:** Cross domain transfer, since there is no cross over opportunity between existing functions
**Fix plan:** Add functions that help cross domain transfer compounding

## Context Connectivity
<!-- How does knowledge flow across teams and domains? Where does it silo? -->

**How knowledge flows:** Support tickets -> Product

**Where it silos:** Implementation feedback is not considered in product development


## Governance Policy

**Scope:** AI features in the maintenance copilot troubleshooting guidance and schedule optimization functions Excludes: General maintenance functions not supported by the copilot

**Autonomy boundaries:** Fixing issues, never auto. Applying schedule optimzation, human approval required. Troubleshooting guidance, auto.

**Escalation triggers:** 1. Multiple attempts are troubleshooting failed and production line is now down 2. Applying schedule optimization messes up the schedule

**Audit cadence:** Monthly, Test readiness for switching verdors (PM). Weekly, Automated smoke test against golden dataset (Devops). Real-time, SRE level monitoring.

**Regulatory exposure (EU AI Act / other):** SOC 2. Risk tier: limited. Controls: maintain audit log of suggestions from the copilot as well as.

## Agent Topology

N/A


## Shadow AI Audit

| Tool | Owner | Risk Level | Decision |
|------|-------|-----------|----------|
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |
| | | H / M / L | keep / govern / kill |

**Total tools found:**
**Tools after triage:**
**Estimated hidden spend:**
