# Agents & Automation

AI agents perform multi-step tasks autonomously -- they can read files, execute code, search the web, and chain operations together. The ethical framework is the same as single-prompt AI, but the stakes are higher because agents process more data with less human oversight per step.

## Claude Code

Command-line AI agent that reads your codebase, writes code, runs tests, and interacts with git.

**Tier depends on auth method, not the product name:**

| Auth Method | Plan | Tier | Training | Agreement |
|---|---|---|---|---|
| Consumer login | Pro ($20/mo) | Tier 1-2 | Default on; toggle off for Tier 2 | ToS |
| Consumer login | Max ($100-200/mo) | Tier 1-2 | Same as Pro | ToS |
| API key (ANTHROPIC_API_KEY) | Pay per token | Tier 3 | No training | DPA (auto-included) |

**Is it ethical to use client data on Claude Pro/Max?** Only if you toggle training off (Tier 2) AND the data is low/medium sensitivity. For high-sensitivity data (identifiable client info), use API key auth (Tier 3).

## Claude Cowork

Browser-based AI workspace (launched January 2026) that uses MCP protocol to connect to external tools (Google Drive, Slack, databases, APIs).

**Same auth-determines-tier rule applies.** The plan you're logged into determines the tier, not the Cowork product itself.

**Warning:** If you connect Cowork to services containing client data (e.g., case management system, Google Drive with case files), the tier of your Cowork session determines the protection level for ALL data flowing through it.

## Metaprompting (Agent-Assisted Prompting)

Ask the AI to write a better prompt for you before you start the actual task:

> "I need to draft a motion to suppress. Before I give you the facts, write me a detailed prompt template that would help an AI produce the best possible suppression motion. Include placeholders for the facts I'll need to fill in."

The AI generates a structured prompt with placeholders. You fill in the placeholders. The AI drafts from the structured input. Better output, less back-and-forth.

## Dashboard Maintenance

Use AI agents to maintain spreadsheets, track deadlines, update case status boards. Low sensitivity as long as you use de-identified references.

## Multi-Agent Workflows

Chain multiple AI calls together:
1. Agent 1 transcribes audio (Reduct)
2. Agent 2 summarizes transcript (Claude API)
3. Agent 3 identifies legal issues (Claude API)
4. Human reviews everything before use

Each agent in the chain needs to meet the minimum tier for the data sensitivity level.

---
*See also: [[Risk-Matrix]], [[Use-Cases]], [[Vendor-Details]]*
