# System notes

Copy this file into the selected workflow's handoff folder as `system-notes.md`. Link existing documentation where it already answers a question. Atab supplies explanations of the source platform; Liam implements the evaluation and simulated environment.

Prepared by: [name and role]

Platform and version or date: [reference]

## Fields and relationships

| Record or table | Field | Meaning and data type | Units, currency or timezone | Allowed values | Related record or key |
| --- | --- | --- | --- | --- | --- |
| [Record] | [Field] | [Meaning] | [Units or not applicable] | [Values] | [Relationship] |

Explain which identifiers connect exports, how null or missing values are represented, and whether timestamps describe creation, an event, an update or an export. Note whether records are current snapshots or historical events and how earlier states can be recovered.

## Actions

| Action | Inputs | Who may perform it | Checks before acceptance | Resulting changes | Failure or rejection behaviour | Side effects or dependencies |
| --- | --- | --- | --- | --- | --- | --- |
| [Action] | [Inputs] | [Role] | [Checks] | [Records changed] | [What happens] | [Other systems, people or messages] |

Describe what happens when an action is retried or corrected, where known. For example, if confirming an order reserves stock, explain both effects and any relevant cancellation behaviour. This is an illustrative question, not an assertion about an Atab platform.

## Rules

| Rule reference | Rule | Source or reviewer | Version or applicable dates | Status |
| --- | --- | --- | --- | --- |
| [RULE-001] | [Description] | [File reference or reviewer] | [Date or unknown] | [Documented / recollection / confirmed by reviewer / needs confirmation] |

Include business constraints and approval rules. Distinguish a source policy from an implementation detail or an assumption.

## Automation and outside work

- Existing rules, scripts or AI features:
- Where people review, correct or override them:
- Relevant work in email, WhatsApp, spreadsheets or other systems:
- Approvals or responses that happen outside the platform:
- Known platform or process changes affecting the supplied date range:

## Gaps and follow-up

List what is not recorded, needs collecting, needs explanation or has permission pending. Identify the person who can help. Ben can arrange a walkthrough or additional access after Liam reviews the exports.
