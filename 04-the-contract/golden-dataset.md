# Golden Dataset & Reliability Contract

## Golden Dataset Spec

Test cases:
  1. Edge: Y · Judge: rule, IN: Invalid error code → OUT: Do not recognize
  2. Edge: N · Judge: both, IN: Valid error code first instance → OUT: Troubleshooting guidance based on context using Frontier model
  3. Edge: N · Judge: both, IN: Valid error code second instance → OUT: Troubleshooting guidance based on context using Cascade model
  4. Edge: Y · Judge: rule, IN: Ask for schedule optimization for invalid production line → OUT: Do no recognize
  5. Edge: N · Judge: LLM, IN: Ask for schedule optimization for valid production line with no production/maintenance history → OUT: New Schedule suggestion with low confidence
  6. Edge: N · Judge: LLM, IN: Ask for schedule optimization for valid production line with rich production/maintenance history → OUT: Schedule optimization suggestion

Dataset health
- Total: 6
- Edge cases: 2 (33.3%)
- Judge mix: 33% rule / 33% LLM / 33% both


**Adversarial rows included:** __
**Coverage gaps identified by partner:**

## Confidence UX Design

## Confidence UX Design

**Approach:** show uncertainty / tiered confidence

**Confident (>90%):** Product troubleshooting help and optimized schedules based on historical data

**Uncertain (50-90%):** When creating schedule for first time, show low confidence by saying it's suggestion.

**Not confident (<50%):** Provide honest 'don't know' answers when encountering error codes/issues or when asked to optimized schedules for invalid assets.

**User control surface:** 

Corrections are captured in the database for future correction of runbook

- Users see AI reasoning / drivers
- Users correct & override outputs
- Users adjust the confidence threshold _(not yet)_
- Corrections feed back into the model / dataset _(not yet)_

## Reliability Contract

## Reliability Contract

| Metric | Target | Measurement | Alert Threshold |
|--------|--------|-------------|-----------------|
| Accuracy | 90 | · | <85% → trigger gold-set audit |
| Hallucination rate | <1 | · | >2 → auto-rollback to last good model |
| Latency (p95) | <500ms | · | >3s → page on-call |
| Drift velocity | <0.25%/wk | · | >0.5%/wk → trigger gold-set audit |

## HITL Architecture

**Trigger:** At a fixed interval (1/week)

**Reviewer:** human would evaluate the feedback/correction made by users

**Feedback loop:** use the input to update the runbook to be used by in future


## Red-Team Findings
*What failure mode did your partner find that you missed?*
