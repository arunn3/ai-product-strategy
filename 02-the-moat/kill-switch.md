# Kill Switch Audit

## Vendor Dependency Assessment

| Dimension | Current State | Risk Level | 48-Hour Action |
|-----------|--------------|------------|---------------|
| **Provider** | *Anthropic*| M | Audit API calls that are not OpenAI compliant|
| **Abstraction** | *Dedicated layer to route AI API calls* | L | Review to ensure easy switching vendor/model references |
| **Routing** | *Need dynamic routing based on task complexity, quality, cost, latency etc.,* | H | Start designing routing into abstraction layer, potentially using an open source decision-maker model in front |
| **Eval** | No Eval | H | Design and start implementing evals |

## Portability Score
<!--  Partial  -->

## If [primary vendor] doubles pricing tomorrow:
<!-- Switch vendor/model references in the abstraction layer, manual testing since there is no eval right now -->

## If [primary vendor] ships a competing product:
<!-- The customer, asset, and line specific runbooks and schedules created so far based on actual usage in the field cannot be replicated -->
