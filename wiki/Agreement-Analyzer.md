# Agreement Analyzer

The [SaaS Agreement Analyzer](submit-agreement.html) is a client-side tool that scans vendor agreements for key data protection clauses.

## How It Works

1. Paste your vendor's Terms of Service, Privacy Policy, or Data Processing Agreement into the text box
2. The tool runs regex pattern matching against 20+ patterns across 9 categories
3. Results are color-coded by concern level (red/yellow/green/blue)
4. Context snippets show the surrounding text for each match

## What It Looks For

| Category | Examples |
|---|---|
| Training | "train," "improve our models," "machine learning" |
| Retention | "retain," "30 days," "delete," "purge" |
| Human Review | "human review," "quality assurance," "annotators" |
| Advertising | "advertising," "personalize," "third-party marketing" |
| DPA/Compliance | "data processing agreement," "SOC 2," "ISO 27001" |
| Content Definitions | "content," "user data," "customer data" |
| Unilateral Changes | "modify these terms," "at our discretion," "without notice" |
| Feedback | "feedback," "thumbs up," "ratings" |
| Legal Process | "law enforcement," "subpoena," "court order," "notify" |

## Privacy

The analyzer runs entirely in your browser. No data is sent to any server. No tracking, no analytics, no cookies.

## Community Submissions

You can optionally email anonymized findings to the community collection address for aggregation. This is voluntary and does not include your original agreement text.

---
*See also: [[Vendor-Details]], [[Risk-Matrix]]*
