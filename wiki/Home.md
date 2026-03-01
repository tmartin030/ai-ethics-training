# AI Ethics & Practical Use -- Training Wiki

This wiki mirrors the [AI Ethics & Practical Use training site](../). It's designed for collaborative editing -- if you find outdated information or want to add a jurisdiction, edit the relevant page directly.

## Pages

| Page | Description |
|------|-------------|
| [[Risk-Matrix]] | 4-tier data protection framework, vendor comparison, scenario analysis |
| [[Use-Cases]] | 13 practical workflows matched to data sensitivity levels |
| [[Agents]] | AI agent patterns, Claude Code, Claude Cowork, automation |
| [[Ethics-Opinions]] | 47+ bar opinions, court policies, case law, comparison table |
| [[Vendor-Details]] | Microsoft, Google, Anthropic, OpenAI, legal AI vendor deep dives |
| [[Glossary]] | 13 key terms for AI data protection |
| [[Agreement-Analyzer]] | How to use the SaaS agreement analyzer tool |

## Quick Reference

**The 4 Tiers:**
- **Tier 1 (Consumer Default):** Trains on your data. ChatGPT Free, Claude Free, Gemini Free.
- **Tier 2 (Consumer Training Off):** No training, but vendor retains data under ToS. ChatGPT Plus (opt out), Claude Pro (toggle off).
- **Tier 3 (API / DPA):** Bilateral contract. No training. Short retention. Anthropic API, OpenAI API, Azure OpenAI.
- **Tier 4 (Enterprise / ZDR):** Zero data retention. Dedicated infrastructure. Harvey, Azure GCC High, M365 Copilot.

**The Rule:**
- Low sensitivity (general research) = Any tier is fine
- Medium sensitivity (de-identified) = Tier 2 minimum, Tier 3 recommended
- High sensitivity (identifiable client data) = Tier 3 minimum, Tier 4 preferred

## Missouri Guidance

Missouri Informal Opinion 2024-11 requires lawyers to:
1. Educate themselves on AI types and risks
2. Assess vendor terms, data security, and how inputs are used
3. Protect confidentiality (Rule 1.6(c))
4. Ensure accuracy of AI work product (candor to tribunals)
5. Supervise nonlawyer AI use

ABA Formal Opinion 512 applies as persuasive authority -- follow it as the floor.

## Contributing

Edit any wiki page directly. For major additions (new jurisdictions, new vendors), create a new page and link it from the relevant index page.
