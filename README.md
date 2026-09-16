# Liam and Atab

This guide gives Ben and the team a bit of context on the data we're looking for, why it helps and what we might build from it.

We start with the business data that's already available. Liam looks through it, with help from the team, to find useful workflows: real jobs where someone uses information, makes decisions and changes something. Once a promising workflow is clear, we can pull together specific examples and understand it in more detail.

## What we're trying to build

The aim is to turn real work into tasks an AI can try, with enough context to act and a way to check the result. An evaluation checks whether it got the task right. A simulated environment lets it work through the steps in a separate system.

To do that, we need to understand what was happening, what information was available, what actions were taken and how the result was judged.

## What data would help

| Data | Why it's useful |
| --- | --- |
| Business records | Orders, stock, suppliers, invoices, requests or other records show what the business is working with. |
| History and changes | Timestamps, status changes, edits and activity logs help show what happened in what order. Human actions and existing automation both matter. |
| Related messages and documents | Emails, WhatsApp messages, spreadsheets and documents can explain requests, decisions or exceptions that the platform alone doesn't show. |
| Rules and outcomes | Instructions, approval rules, completed work and corrections help us understand what a good result looks like. |

Send what exists and flag what doesn't. A small sample of related records is a useful starting point; the first step is understanding what is available.

## How the process works

1. Ben gives Liam an overview of the platforms and the types of data available, then shares an accessible sample privately.
2. Liam reviews the data with the team's help and looks for recurring jobs, decisions, exceptions and outcomes that can be checked.
3. We narrow down the promising workflows and follow up on specific records or explanations.
4. Liam turns the supported workflows into evaluation tasks or simulated environments, with someone who knows the business checking that they make sense.

Workflow selection comes after the first look at the data. Ben's initial role is to help surface the available records and explain what they represent.

## An example

Order, stock and supplier records might reveal cases where an order couldn't be fulfilled as planned. Related messages and changes could show how someone spotted the problem, chose another option and updated the order.

That could become a task where an AI has to resolve a similar situation while respecting stock, deadlines and approvals. The actual records will tell us whether this is a useful direction. It's an illustration, rather than a workflow already selected for Atab.

## What to send first

- Which platforms have real use and what each stores. YourMart, Nutrigo and Replay are possible starting points; another client is fine.
- Existing exports or a sample of related records, with the period covered.
- A few notes on what the files mean and how they connect.
- Any existing docs or rules that help explain them.
- Who can answer questions about the software and the business.

The [company and data prompts](templates/company-profile.md) and [quick checklist](handoff-checklist.md) can help. Existing docs and short answers are fine. Send client files and filled-in notes privately to Liam.

## More detail if useful

The [full guide](brief.md) and [Word copy](deliverables/Ben%20-%20Liam%20and%20Atab%20data%20brief.docx) explain the idea in one place. There are also [platform prompts](system-notes/README.md), a [folder example](handoffs/README.md) and [sharing notes](permissions.md).

The [workflow](templates/workflow.md) and [case](templates/case.md) prompts are for later, once we've seen the data and know what to explore. They don't need filling in for the first handoff.
