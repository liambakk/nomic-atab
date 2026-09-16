# Liam and Atab data handoff

Ben and the Atab team provide records and explanations of real business work. Liam uses them to build tasks and simulated environments that AI labs can use to evaluate and train models.

This repository explains the first handoff and gives the team templates to complete. The starting request is one company, one workflow and three completed cases, where available. The company, workflow, effort and delivery date still need to be agreed with Ben.

## Start here

Use [Issues](https://github.com/liambakk/nomic-atab/issues) to track the starting decisions and open questions.

1. Ben: recommend the company and workflow with the clearest real records. Start with YourMart, Nutrigo or Replay if suitable; another client is welcome. Confirm what is actually live before selecting it.
2. Ben and Liam: agree the choice, preparation effort, permission for the first review and a proposed handoff date. Ben identifies a technical contact and someone who does the work at the business.
3. Atab team: prepare the records for one routine case and two cases involving an exception, investigation or correction, where available. Use the templates below and flag missing information.
4. Ben: share the records privately with Liam and arrange a proposed 30-minute walkthrough with the relevant people.
5. Liam: review the evidence, resolve questions with the business reviewer and build the initial evaluation or environment sample.

The immediate outcome is a usable first sample for assessment. Additional collection and any commercial delivery are agreed after that review.

## Read the brief

- [Read the full brief](brief.md)
- [Download the Word brief](deliverables/Ben%20-%20Liam%20and%20Atab%20data%20brief.docx)
- [Follow the handoff checklist](handoff-checklist.md)

The Word document retains the agreed Helvetica formatting. The same wording is maintained in `brief.md`.

## What each person provides

| Person | Responsibility |
| --- | --- |
| Ben | Coordinate the company choice, access, team support, permissions, effort and handoff date. Ben is Liam's contact for Atab. |
| Atab team | Export the available records and explain the platform, fields, actions, history and automation. |
| Business reviewer | Explain the actual work and validate rules, outcomes and acceptable alternatives. Ben identifies this person. |
| Liam | Design and build evaluations, environment actions and scoring; test models; manage lab conversations and delivery. |

## Fill in these templates

Copy the templates into a folder under `handoffs/` for the selected company and workflow. The [folder instructions](handoffs/README.md) show how. Alternatively, send the completed answers and records to Liam; he can maintain the files here. Using Git is optional for the first handoff.

| Template | What it captures |
| --- | --- |
| [Company profile](templates/company-profile.md) | The business, live software, available history and relevant contacts. |
| [Workflow](templates/workflow.md) | The job, its trigger, steps, decisions, rules and typical exceptions. |
| [Completed case](templates/case.md) | What was known, what happened, the connected evidence and how the result was assessed. Copy once per case. |
| [System notes](system-notes/README.md) | Field meanings, relationships, actions, rules and existing automation. |
| [Permission record](permissions.md) | The status and limits of each proposed use of the material. |

Use `not recorded`, `needs collecting`, `needs explanation` or `permission pending` for gaps. Include who can help where known. Send the usable material available; flag fewer than three cases rather than inventing examples or history.

## Keep the evidence connected

Store source exports in a private folder agreed with Liam. Keep an index in [data-manifest.csv](data-manifest.csv), using stable file and case references. [Record handling](data/README.md) explains the fields and how to link records without putting raw exports in this repository.

Use [Issues](https://github.com/liambakk/nomic-atab/issues) for questions, missing information and cases ready for review. Record confirmed answers in the relevant file and [decision log](decisions.md), with the reviewer and date. The repository contains templates at setup; no company records or completed cases have been supplied here yet.

## Working together

[Contribution instructions](CONTRIBUTING.md) cover browser edits, questions and review. [Document maintenance](docs/maintenance.md) covers regenerating the Word brief after wording changes. These technical maintenance steps are for Liam or an engineer and are not required to prepare the first handoff.
