# Glossary

Key terms for AI data protection. Understanding these is essential for evaluating any AI tool's data practices.

**Training** -- The process of feeding data into an AI model to change its future behavior. Your data becomes part of the product other people use. Not the same as inference.

**Inference** -- When the AI reads your prompt and generates a response. Temporary by nature. The ethical question is what happens to your data *after* inference.

**Prompts** -- What you type into the AI tool. The primary vector for confidentiality risk.

**Responses** -- What the AI generates back. Can also contain sensitive information because they reflect what you told the model.

**Content** -- Umbrella term vendors use in ToS for prompts + responses + uploads + feedback. Read carefully -- some vendors define it to include metadata and usage patterns.

**Personal Data** -- Any information that identifies or could identify a specific person. In criminal defense: client names, case numbers, DOB, SSN, victim/witness names, unique fact patterns.

**DPA vs. ToS** -- A Data Processing Agreement is a bilateral contract binding the provider to specific obligations. Terms of Service are the provider's rules that they can change unilaterally. API = DPA. Consumer = ToS. *This is the most important distinction in the entire framework.*

**Data Processor vs. Data Controller** -- A processor handles your data on your behalf following your instructions. A controller decides purposes and means of processing. You want your AI provider to be a processor.

**Data Handler** -- Any entity that touches your data in the pipeline. In Clio Duo: Clio + Azure + OpenAI. A chain is only as strong as its weakest link.

**Zero Data Retention (ZDR)** -- Provider deletes data immediately after processing. Gold standard. Some vendors use "ZDR" loosely to mean 30-day retention.

**Legal Process Notification** -- Whether the vendor tells you before handing your data to law enforcement. Critical because privilege must be actively asserted. ABA 512 requires confirming this.

**"No Human Review"** -- No humans routinely read your data for quality improvement. But carve-outs exist for: legal process, safety/CSAM, ToS violations, security incidents.

**Re-identification Risk** -- Even de-identified data can reveal a client's identity. Context accumulates across a conversation. If a stranger reading your prompts could figure out who the client is, treat it as identifiable.

---
*See also: [[Risk-Matrix]], [[Ethics-Opinions]], [[Vendor-Details]]*
