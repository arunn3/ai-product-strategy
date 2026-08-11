# Data Flywheel Map

> Score each loop 1-5. Your weakest loop is where competitors attack first.
> The four loops below are the M2 starting point - adapt if your product has 2 or 6 loops instead of 4.

## Flywheel Loops

| Loop | What It Measures | Score 1 | Score 5 | Score |
|------|------------------|---------|---------|-------|
| **Correction** | Do users fix AI outputs? Is that signal captured and reused? | No capture | Automated retraining | 2/5 |
| **Preference** | Does the product learn individual / team preferences over time? | Stateless | Deep personalization | 3/5 |
| **Domain Context** | Does usage in one area improve quality in adjacent areas? | Siloed | Cross-domain transfer | 1/5 |
| **Network** | Does each new user / team make the product better for everyone? | Isolated | Strong network effects | 3/5 |

### Correction Loop - 2/5
**What you capture today:**
*We capture whether the troubleshooting advice given by the assistant helped the user resolve the issue.*
**How it compounds:**
*The feedback is manually reviewed and used as input to create runbook for AI*

### Preference Loop - 3/5
**What you capture today:**
*The product reviews historical data of scheduled and breakdown maintenance events on a given line to tailor new schedules that minimize breakdown maintenance*
**How it compounds:**
*The deep information about which machines require maintenance at what intervals to avoid downtime is very specific to a line in the factory - comparable to user preferences*

### Domain Context Loop - 1/5
**What you capture today:**
*Currently there's no domain context loop/cross domain transfer since the two functionality offered doesn't have cross domain relationship*
**How it compounds:**
*No compounding*

### Network Loop - 3/5
**What you capture today:**
*The troubleshooting help accuracy feedback is captured*
**How it compounds:**
*The user feedback about troubleshooting accuracy is used to improve the AI knowledge-base*

**Total Flywheel Score: 9/20**
**Weakest Loop:**
*Domain Context Loop*
**Fix for weakest loop:**
*since current functions do not have cross domain transfer opportunity, we should add new functionality that support cross domain transfer*
---

## Encroachment Threat Assessment

### 1. Platform Encroachment
**Attacker:**
*OpenAI*
**Vector:**
*Troubleshooting Support*
**Time-to-threat:**
*6 months*
**% of value at risk:**
*50%*

### 2. Vertical Competitor
**Attacker:**
*IBM-Maximo*
**Vector:**
*Schedule optimization and troubleshooting help*
**Time-to-threat:**
*6-12 months*
**% of value at risk:**
*100%*

### 3. Adjacent Expansion
**Attacker:**
*Palantir*
**Vector:**
*Schedule optimization*
**Time-to-threat:**
*12 months*
**% of value at risk:**
*50%*
---

## 90-Day Encroachment Plan

*Your partner played the Big Tech attacker. What was their plan to kill you?*

**Attacker:**
**Attack vector (target the weakest loop):**
**Weeks 1-4 - what they ship:**
**Weeks 5-8 - how they poach users:**
**Weeks 9-12 - why users don't come back:**
**Your defense:**
