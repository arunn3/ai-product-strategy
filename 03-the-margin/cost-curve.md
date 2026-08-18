# Cost Curve & Pricing Strategy

## Cost Model

| Cost Category | Per-User/Month | Notes |
|--------------|----------------|-------|
| Inference (primary model) |$12|Sonnet 5 |
| Inference (cascading/triage) |$6 | Haiku 4.5 |
| Infrastructure | $1| Azure, minimal since most of infra is on-prem at customer site|
| Data/storage | $1| Azure, minimal|
| Human-in-the-loop | $10| For review of feedback and updating the runbook |
| **Total AI COGS** | $30| |

## Cascading Strategy
<!-- Cheap model → frontier model routing logic -->

**Triage model:** Haiku 4.5
**Frontier model:** Sonnet 5.0
**Routing rule:** If the issue being troubleshoot has been experienced before, route to Haiku with previous instances data.
**Expected cascade ratio:** 70%

## Pricing Model

**Current pricing: N/A**<br>
**Proposed AI pricing:**<br>
*Strategy posture:* Penetrate<br>
*Pricing model:* Outcome / Resolution<br>
*Unit of work metered:* troubleshooting sessions<br>
*Base fee ($/month):* 20<br>
*Price per unit:* $3<br>
*Estimated units/user/month:* 5<br>
*Implied revenue/user/month:* $35.00<br>
**Model:** outcome-based<br>

## Stress Tests

| Scenario | Impact on Margin | Response |
|----------|-----------------|----------|
| Inference costs 3x |-33% | Increase unit price|
| Heaviest segment doubles | +50%| No action|
| Model provider raises prices 50% | -16%| Increase unit price |

## Board One-Pager
<!-- Before/After: Old SaaS revenue vs. AI usage revenue for your product -->

**Before (traditional SaaS):**
**After (AI-enabled):**
**Net margin shift:**
