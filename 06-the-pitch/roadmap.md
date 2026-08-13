# Three-Horizon Roadmap & Board Pitch

## Roadmap

## Horizon 1, Ship (0-4 weeks)

| Initiative | Strategy Component | Why it ships now | Confidence |
| :-- | :-- | :-- | :-- |
| Troubleshooting Assistance to troubleshoot manufacturing operational issues | Bet | This is the product’s stated core job: operator support during troubleshooting. Ship a narrow, auditable version using existing runbooks, explicit uncertainty, and escalation paths. | H |
| Implement cascade/routing between frontier model and lightweight model; increase %requests routed to cascade model | Margin | The strategy already defines a Haiku/Sonnet cascade posture and a \$30 break-even target. Routing is an enabling control for reducing AI COGS before usage scales. | H |

## Horizon 2, Validate (1-3 months)

| Initiative | Strategy Component | Hypothesis | Kill Criteria | Confidence |
| :-- | :-- | :-- | :-- | :-- |
| Schedule Optimizer to optimize the maintenance schedule of a specific asset based on past data | Bet | If the copilot recommends asset-level maintenance schedules using historical maintenance and operating data, planners will accept recommendations that improve schedule quality without creating operational disruption. | If we do not see at least 60% planner acceptance of recommendations and a measurable improvement in one agreed scheduling metric by week 8, we stop. | M |
| Downtime reducer to reduce overall downtime by identifying optimal schedule to maintain entire line | Moat | If scheduling can incorporate line-level dependencies, the product can create differentiated cross-asset operational context that is harder for a generic copilot to reproduce. | If we cannot assemble reliable dependency, downtime, and maintenance-history data for one line and demonstrate a better simulated outcome than asset-level scheduling by week 10, we stop. | L |

## Horizon 3, Explore (3-6 months)

| Initiative | Strategy Component | What must be true first | Confidence |
| :-- | :-- | :-- | :-- |
| Work instruction generator for improvement in maintenance execution accuracy and speed | Moat | Troubleshooting guidance must show that users consistently consume, correct, and validate AI-generated maintenance knowledge; otherwise generated work instructions will amplify unverified content rather than strengthen the Domain Context Loop. | M |

## Unmapped (cut or rethink)

| Initiative | Why it's unmapped | Recommendation |
| :-- | :-- | :-- |
| None | Every listed initiative connects to the core product, economic model, or identified moat gap. | Keep the list constrained to these initiatives; do not add adjacent “general maintenance AI” features until the H2 scheduling evidence is in. |

## Board Pitch

**Thesis (1 sentence):**

**The case:**
1. Why now:
2. What's defensible:
3. The economics:

**The risks:**
1. Trust / failure modes:
2. Scale / governance:
3. Competitive:

**The ask:**

## M1 Baseline vs. Now
*Your 3-sentence AI strategy from Module 1 vs. what you'd say now:*

**M1 baseline:**

**Now:**
