# Three-Axis Vulnerability Diagnostic

## Product
MMS-AI (Maintenance Assistant/Co-pilot)

**Product:**
Product Leader

---

## Scores

### Contextual Moat — 3/5
*Workflow depth × switching cost. Would users leave in a weekend if a competitor showed up?*

**Score rationale:**
*Our main product (maintenance management system - MMS) is used in factories and is embedded in the daily workflow of tens-hundreds on people in customer sites depending on the size of the factory. There is also a lot of initial data setup and customization involved.  
The Maintenance Assistant is a chat interface add-on that help with maintenance scheduling, operator support during troubleshooting. 
Smaller customers with simpler workflows could potentially vibe-code a simple maintenance management system and the AI assistance on top, however larger customers would find it better to stick with us due to migration effort, support requirements, and operator training etc., involved with the main product MMS* 

**Named attacker (from partner challenge):**
*From among platform providers, Microsoft is a potential attacker as they have maintenance capabilities within MS Dynamics 365 suite even though currently not deep functionality*

---

### Data Advantage — 4/5
*Proprietary signal that compounds with usage. What do you see that OpenAI doesn't?*

**Score rationale:**
*We could use the past maintenance data in the DB to provide insights on how to improve/optimize maintenance schedules for specific assets in the factory which a generic model/platform cannot provide.* 

**Named attacker (from partner challenge):**
*Any platform provider could provide similar chat/copilot interface, however it would be missing the historical maintenance data and asset information that only we have*
---

### Platform Exposure — 4/5
*Encroachment risk × pivot speed. If Apple/Google/OpenAI ships your hero feature native — then what?*

**Score rationale:**
*MMS workflow integration and data advantage is our defense. Customers would find it difficult to migrate the workflows to the platform and retrain the users while daily operations continue to add more data into our system* 

**Named attacker (from partner challenge):**

---

## Top Vulnerability
<!-- One line: what's the single biggest strategic risk? -->

## Confidence Level
<!-- H / M / L — how confident are you in this bet after the diagnostic? -->
