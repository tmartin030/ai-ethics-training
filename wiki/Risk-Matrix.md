# Risk Matrix

The risk matrix maps **data sensitivity** (rows) against **protection tier** (columns) to produce a risk assessment for any AI use scenario.

## The Grid

|  | Tier 1 (Consumer) | Tier 2 (Training Off) | Tier 3 (API/DPA) | Tier 4 (Enterprise) |
|---|---|---|---|---|
| **High (PII)** | RED | RED | GREEN | GREEN |
| **Medium (de-ID)** | YELLOW | YELLOW | GREEN | GREEN |
| **Low (research)** | GREEN | GREEN | GREEN | GREEN |

## Sensitivity Levels

### Low Sensitivity
General legal research, statutory analysis, case law questions, brainstorming, writing templates. No client-identifying information.

### Medium Sensitivity
De-identified case information. Client name, case number, and unique identifiers removed. **Warning:** Re-identification risk increases with conversation length -- a 50-message thread about the same case can become identifiable even without names.

### High Sensitivity
Identifiable client data. Names, case numbers, DOB, SSN, police reports, confessions, victim/witness information, unique fact patterns.

## Protection Tiers

### Tier 1 -- Consumer Default
- **Agreement:** Terms of Service (unilateral)
- **Training:** YES -- your data trains the model
- **Retention:** Indefinite
- **Human review:** Yes (quality raters, including contractors)
- **Examples:** ChatGPT Free, Claude Free, Gemini Free, Perplexity Free, Copilot Free

### Tier 2 -- Consumer Training Off
- **Agreement:** Terms of Service (unilateral)
- **Training:** No (if you toggle it off)
- **Retention:** 30 days to indefinite depending on vendor
- **Human review:** Varies -- some retain for safety review
- **Examples:** ChatGPT Plus/Team (opt out), Claude Pro/Max (toggle off)

### Tier 3 -- API / DPA
- **Agreement:** Data Processing Agreement (bilateral contract)
- **Training:** No
- **Retention:** 7-30 days (abuse monitoring), then deleted
- **Human review:** No routine review; safety carve-outs only
- **Examples:** Anthropic API, OpenAI API, Azure OpenAI, Google Cloud Vertex AI

### Tier 4 -- Enterprise / ZDR
- **Agreement:** Enterprise agreement with DPA, BAA, custom terms
- **Training:** No
- **Retention:** Zero data retention or customer-controlled
- **Human review:** No
- **Examples:** Harvey, Azure GCC High, M365 Copilot (enterprise), Clio Duo (via Azure)

## Feedback Trap

When you click thumbs up/down on an AI response, you give the vendor that entire conversation for training -- even if you've opted out of general training.

- **OpenAI:** Feedback-flagged conversations retained even in Temporary Chat mode
- **Anthropic:** Feedback data retained up to 5 years; not opt-outable via the training toggle
- **Google:** Similar retention for feedback data

**Never provide feedback on conversations containing client information.**

## Key Case Law

- **United States v. Heppner** (S.D.N.Y. Feb. 2026): Consumer AI chat logs not privileged. "Simply no reasonable expectation of confidentiality" under consumer ToS. Enterprise/API tiers distinguished.
- **NYT v. OpenAI** (S.D.N.Y. Nov. 2025): 20 million de-identified ChatGPT logs ordered produced in discovery. AI chat logs treated as standard ESI.

---
*See also: [[Ethics-Opinions]], [[Vendor-Details]], [[Glossary]]*
