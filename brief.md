# Business data handoff brief

Liam and Atab

Prepared for Ben and the Atab team | 15 September 2026

## Purpose and initial scope

Liam will use records of real business work to build AI evaluations and simulated environments. An evaluation checks whether an AI completes a task correctly. An environment lets the AI inspect records, take actions and repeat the task in a separate system.

The proposed first handoff covers one company, one workflow and three completed cases. Its purpose is to assess the available records, build an initial sample and test buyer interest. The company and workflow will be selected with Ben before the cases are prepared.

## Responsibilities

| Owner | Responsibility |
| --- | --- |
| Ben | Coordinate the client selection, source access, team support, permissions and proposed handoff date. Ben is Liam's point of contact for Atab. |
| Atab team | Supply the relevant records and explain the software, fields, actions and existing automation. |
| Business reviewer | Explain how the work is done and check the rules and acceptable outcomes. Ben identifies a suitable person at the selected business. |
| Liam | Select tasks; build the evaluations, environment, actions and scoring; test models; handle lab conversations and delivery of the lab product. |

## 1 Select the company and workflow

Provide a short profile of YourMart, Nutrigo and Replay, or another client with better available examples. For each candidate, cover:

- Business and software: what the company does and which work Atab's platform handles.
- Live use: whether the platform is live, when use began and roughly how many people use it.
- Recurring work: two or three jobs, their approximate frequency, and where decisions, approvals, exceptions or corrections occur.
- Available history: the date range of records and whether changes are saved or only current values exist.
- Other sources: relevant emails, WhatsApp messages, spreadsheets, documents or calls outside the platform.
- Business contact: a person who regularly does the work and can explain actual cases.

Output: a recommended company and workflow, with a short reason for choosing them. Estimates are acceptable. Flag any platform awaiting launch and describe what it will capture.

<!-- pagebreak -->

## 2 Prepare three completed cases

A case is one actual piece of work from its original request or trigger to its outcome. Select one routine case and two involving investigation, a decision or a correction, where available. Include mistakes and failed attempts within the cases, as well as the eventual result.

### Required information for each case

| Required item | What to include |
| --- | --- |
| Request and goal | The original request or trigger, date, desired result, deadline and order, ticket or other case reference. |
| Starting information | The records available before the employee acted, including relevant stock, commitments, previous messages or documents. |
| Rules and constraints | Instructions, policies, approval limits and other constraints that applied at the time. Identify unwritten rules and who explained them. |
| Actions and decisions | The sequence of actions, actor or role, timestamp and resulting changes. Include messages, approvals, rejected actions and corrections. Separate human actions from automatic changes. |
| Actual outcome | Final records and evidence of what happened. Identify anything unresolved or unsuccessful. Keep promised dates and actual dates separate. |
| Assessment of the result | Why the outcome was acceptable or unacceptable, what would count as an error and whether another resolution could also have been valid. Identify who can check this. |

Use original records wherever possible. Preserve timestamps and references so Liam can connect the files and distinguish information known during the work from information learned afterwards.

### Inventory example

For an order that could not be fulfilled as requested, useful records could include the original order, stock and existing reservations, supplier updates, applicable rules, the employee's decision, approvals or customer agreement, and final fulfilment records. Select a real case and include the evidence that explains the decisions.

### Missing information

Mark any missing history explicitly. An explanation from memory can help, but label it as a recollection. If fewer than three usable cases exist, provide the available cases and list the gaps. Liam will assess whether further collection is worthwhile.

<!-- pagebreak -->

## 3 Package the records and system notes

Supply CSV, JSON or spreadsheet exports, with relevant original documents and messages alongside them. Screenshots or screen recordings can explain how the software is used. Keep shared records in one place and reference them from the relevant cases.

### Folder contents

| Folder or file | Contents |
| --- | --- |
| Company and workflow | The selected company profile, workflow description, source date range and business contact. |
| Cases | Separate Case 1, Case 2 and Case 3 folders containing the records and explanation required in section 2. |
| Rules and instructions | Relevant policies, operating notes and approval limits, with dates or versions where available. |
| System notes | Field definitions, record relationships, action behaviour and existing automation, as described below. |
| Handoff notes | An index of files, known gaps, permission status, contact for questions and proposed walkthrough time. |

### System explanations

Existing documentation, API descriptions or a walkthrough may cover these points:

- Fields: meanings of key IDs, fields and statuses, including units, currencies and timezones.
- Relationships and history: how records connect and whether each export contains historical changes or only current values.
- Actions: what each relevant action changes, who can perform it, and what causes acceptance or rejection.
- Dependencies: steps that rely on another person or system and how the response affects subsequent work.
- Automation: rules, scripts or AI features already involved, including where people review or override them.

For example, if confirming an order also reserves stock, explain both changes. Liam uses this information to implement the simulated actions, resets and checks.

### Record handling and access

Preserve the IDs, timestamps, quantities and relationships needed to understand each case. If names or identifiers are replaced, use consistent replacements across files and note the changes.

List gaps as not recorded, needs collecting, needs explanation or permission pending, with the person who can help where known. Share the folder privately with Liam. Any additional walkthrough or separate read-only access can be arranged through Ben after the exports are reviewed.

<!-- pagebreak -->

## 4 Confirm permissions and complete the handoff

### Permitted uses

Ben should identify what existing agreements allow and who can approve any additional use. Record the status of each proposed use:

- Sharing source records and business rules with Liam to build evaluations and environments.
- Testing models, including providing selected material to model providers where needed.
- Showing selected examples and results privately to prospective lab buyers.
- Commercially licensing the resulting records, tasks or simulated examples for evaluation or training, including reuse across buyers where permitted.

Note restrictions on confidential information, personal or third-party data, recipients, reuse and retention. Obtain any additional approval in writing before the relevant use. Flag separate restrictions on Atab software or code if either becomes necessary.

### Time and commercial arrangements

Provide an estimate of the preparation effort and cost, including Atab team and client time, for agreement with Liam before that work is incurred. Before committing to a commercial delivery, agree payment or revenue sharing for Atab and any participating business, and the ongoing work covered by those terms.

### Submission checklist

Before sharing the first set, confirm that:

- The company and workflow are identified, and the files have a clear index.
- The available cases include connected source records and explanations, with gaps labelled.
- The business rules, system behaviour and available history are explained or assigned to a person for follow-up.
- Permission status and any limits are recorded, and material shared with Liam is cleared for that step.
- The preparation effort or cost is agreed, and Ben has proposed a handoff date and walkthrough time.

### Review and next steps

Atab handoff: Ben coordinates the private folder delivery and a proposed 30-minute walkthrough with Liam. Include the relevant Atab team member and business reviewer where their input is needed.

Liam's review: Liam checks the cases, identifies missing information and proposes initial tasks. The business reviewer checks the starting information, rules and acceptable outcomes before Liam relies on them for scoring.

Further supply: Liam brings any later request for additional records, format, timing and support back to Ben. Atab should flag whether fresh cases, corrections and dated process or automation changes are already available. Additional collection and recurring delivery are scoped after the first review.
