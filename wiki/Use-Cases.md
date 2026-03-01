# Use Cases

13 practical workflows for criminal defense attorneys, matched to data sensitivity levels and minimum protection tiers.

## Low Sensitivity (Any Tier)

### 1. Legal Research
Ask AI to explain statutes, find case law patterns, compare jurisdictions. No client data needed.

### 2. Jury Selection Brainstorming
General voir dire strategies, question templates, bias research. Keep it abstract.

### 3. Continuing Education
Summarize articles, explain legal concepts, prep for CLE presentations.

### 4. Writing Templates
Motion shells, letter templates, office procedure documents. No client facts.

### 5. Statutory Analysis
"What are the elements of X under RSMo Y?" Pure legal questions.

## Medium Sensitivity (Tier 2 minimum, Tier 3 recommended)

### 6. De-identified Case Strategy
Remove names, case numbers, and unique identifiers before discussing case theory. Watch for re-identification risk in long conversations.

### 7. Sentencing Research
De-identified discussion of sentencing ranges, mitigating factors, comparable outcomes.

## High Sensitivity (Tier 3 minimum, Tier 4 preferred)

### 8. Motion Drafting with Client Facts
Drafting motions that include specific client information, case facts, or evidence details. Requires API tier or enterprise tool.

### 9. Discovery Analysis
Uploading or discussing police reports, witness statements, forensic reports. Use enterprise-tier tools only.

### 10. Client Confession Analysis
Analyzing statements, identifying suppression issues, Miranda analysis. Highest sensitivity -- Tier 3 minimum, Tier 4 strongly preferred.

### 11. Body-Worn Camera Transcription
**Recommended tool: Reduct** (MSPD has enterprise agreement). Handles video natively, links transcripts to timestamps.

**Alternatives:**
- JusticeText -- built for public defenders, timestamps linked to video
- Word Transcribe (M365) -- limited: no native video, one file at a time, accuracy drops with poor audio

### 12. Plea Negotiation Prep
Analyzing offers against sentencing guidelines with specific client facts. Tier 3+ only.

### 13. Expert Witness Prep
Reviewing expert reports, preparing cross-examination with case-specific details. Tier 3+ only.

## Two-Stage Workflow

For medium/high sensitivity work on consumer-tier tools:

1. **Stage 1 (Any tier):** Ask the AI to generate a template, framework, or analysis structure using generic/hypothetical facts
2. **Stage 2 (Local):** Fill in your actual client information locally in Word/document editor -- never send it to the AI

This lets you use consumer-tier AI for the intellectual heavy lifting while keeping client data off the platform entirely.

---
*See also: [[Risk-Matrix]], [[Agents]], [[Glossary]]*
