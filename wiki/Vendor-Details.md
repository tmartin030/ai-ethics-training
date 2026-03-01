# Vendor Details

Deep dives on platform vendors, legal AI vendors, and transcription tools. Pricing as of March 2026.

## Platform Vendors

### Microsoft

| Product | Tier | Price | Training | DPA |
|---|---|---|---|---|
| Copilot Free (copilot.microsoft.com) | 1 | Free | Yes, data used for ads | ToS |
| Copilot Pro | 2 | $20/mo | No training; 30-day retention | ToS |
| M365 Copilot (enterprise) | 4 | $30/user/mo add-on | No training; stays in tenant | Enterprise agreement |
| Azure OpenAI Service | 3-4 | Pay per token | No training; DPA | DPA |
| Azure GCC High | 4 | Custom | ZDR; FedRAMP High | Enterprise + BAA |

**M365 license changes (July 2026):** E3 rises to $42/user/mo, E5 to $65/user/mo. Copilot stays $30 add-on.

**ABA 512 compliance:** M365 Copilot and Azure OpenAI meet all ABA 512 requirements at enterprise tier. Copilot Free does NOT.

### Google

| Product | Tier | Price |
|---|---|---|
| Gemini Free (personal) | 1 | Free |
| Gemini in Workspace (Business Starter) | 4 | $7/user/mo |
| Gemini in Workspace (Business Standard) | 4 | $14/user/mo |
| Gemini in Workspace (Business Plus) | 4 | $18/user/mo |
| Gemini in Workspace (Enterprise) | 4 | $22/user/mo |
| Vertex AI (API) | 3-4 | Pay per token |

**Key insight:** Even the cheapest Workspace plan ($7/user/mo) gets Tier 4 protection -- data stays in your tenant, no training, enterprise DPA.

### Anthropic (Claude)

| Product | Tier | Price |
|---|---|---|
| Claude Free | 1 | Free |
| Claude Pro | 1-2 | $20/mo (toggle training off for Tier 2) |
| Claude Max | 1-2 | $100-200/mo |
| Claude Team | 3 | $30/user/mo |
| Claude Enterprise | 4 | Custom |
| API (Haiku 4.5) | 3 | $1/$5 per M input/output tokens |
| API (Sonnet 4.6) | 3 | $3/$15 per M tokens |
| API (Opus 4.6) | 3 | $5/$25 per M tokens |

### OpenAI

| Product | Tier | Price |
|---|---|---|
| ChatGPT Free | 1 | Free |
| ChatGPT Plus | 1-2 | $20/mo |
| ChatGPT Team | 3 | $30/user/mo |
| ChatGPT Enterprise | 4 | Custom |
| API | 3 | Pay per token |

## Legal AI Vendors

| Vendor | Price | Tier | Focus |
|---|---|---|---|
| Paxton AI | $159-199/user/mo | 3 | Legal research, drafting |
| CoCounsel (Thomson Reuters) | $225/user/mo | 4 | Bundled with Westlaw |
| vLex Vincent | $399/mo | 3-4 | Research, drafting, analysis |
| Clio Duo | $39/user/mo | 3-4 | Practice management AI (via Azure) |
| Harvey | $100-500/user/mo | 4 | Enterprise legal AI (Am Law firms) |
| Lexis+ Protege | Contact sales | 4 | Bundled with Lexis+ |
| WexlerAI | Contact sales | 3-4 | UK-based litigation AI |

## Transcription Tools

| Tool | Price | Best For |
|---|---|---|
| Reduct | MSPD enterprise | BWC video, depositions (MSPD recommended) |
| JusticeText | PD pricing available | Public defender transcription |
| Everlaw | Enterprise | FedRAMP-certified, large-scale review |
| Word Transcribe (M365) | Included | Short, clear audio only |

## What to Ask Any AI Vendor

1. Does the platform train on my inputs? Can I opt out? Is opt-out retroactive?
2. Will you sign a DPA? What does it cover?
3. How long do you retain my data after processing?
4. Is feedback data (thumbs up/down) treated differently from conversation data?
5. Can humans at your company read my conversations? Under what circumstances?
6. Who are your subprocessors and what data do they see?
7. What certifications do you hold? (SOC 2 Type II, ISO 27001, FedRAMP?)
8. Will you notify me before responding to legal process involving my data?

---
*See also: [[Risk-Matrix]], [[Ethics-Opinions]], [[Glossary]]*
