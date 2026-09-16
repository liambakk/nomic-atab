# Atab data and workflow guide

Liam and Atab

For Ben and the Atab team

## The idea

Start with the business data that is already available, then look for useful workflows within it. Ben and the team help surface the records and explain what they mean. Liam reviews them, identifies promising work to model and follows up on the details.

The aim is to turn real work into tasks an AI can try. An evaluation checks whether it got the result right. A simulated environment lets it work through the steps in a separate system, using realistic information, actions and rules.

Workflow selection comes after the first look at the data. For now, an overview of what exists and a sample of connected records will help us see where to start.

## What data helps and why

| Data | What it helps us understand |
| --- | --- |
| Business records | Orders, stock, suppliers, invoices, requests or similar records show the situation people are working with. The relevant records depend on the platform. |
| History and changes | Timestamps, status changes, edits and activity logs show what happened and in what order. Include human actions and existing automation where recorded. |
| Related messages and documents | Emails, WhatsApp messages, spreadsheets and documents can explain the request, the decision or an exception that is missing from the platform records. |
| Rules and outcomes | Instructions, approvals, completed work and corrections help explain what was allowed and whether the result was good or bad. |

The useful part is being able to connect these records. For example, an order reference might link the request, stock changes, supplier messages and final delivery. Keep those links and timestamps where available.

## What would help from Ben first

- A short overview of the platforms, what each stores and which have real use. YourMart, Nutrigo and Replay are possible starting points; another client is fine.
- An existing export or a small sample of related records, with a note on the period covered and anything left out.
- A few notes on what the files and key fields mean, how records connect and whether earlier changes are saved.
- Existing docs, rules or examples that help explain the data.
- Someone at Atab who knows the software and someone at the business who can answer questions about the work.

Use what already exists. CSV, JSON, spreadsheets, documents and short notes are all useful. A walkthrough can fill in explanations. If a platform is not live or some history is missing, just flag it.

<!-- pagebreak -->

## What we look for in the data

A workflow is a real job with a start, a set of actions or decisions and an outcome. We look for work where someone has to connect information, apply rules, handle an exception or choose between options, and where we can check whether the result makes sense.

Some examples of what the data might reveal:

- Orders, stock and supplier updates could show how people resolve shortages or delayed deliveries.
- Invoices, payments and corrections could show how people investigate a mismatch and fix the relevant records.
- Requests, availability and approval records could show how people choose a workable option when there are constraints or conflicts.

These are examples to give the team a sense of what helps. We will see which directions the actual data supports. A promising workflow needs enough context to reconstruct the work and a sensible way to assess the result.

### An inventory example

Suppose the records show an order that could not be fulfilled as planned. Stock history, supplier updates and messages may explain how someone spotted the problem, chose an alternative and changed the order.

That could become a task where an AI works through a similar situation while respecting stock, deadlines and approvals. To understand it properly, we would then ask for the specific linked records and someone who can explain why the chosen outcome was acceptable.

## How we work through it

- First, Ben and the team share what data is available and a useful starting sample.
- Liam looks through it and asks questions to understand the records and the work behind them.
- We identify promising workflows and gather more detail on specific examples, including routine cases, exceptions and corrections where available.
- Liam builds and tests the evaluation or simulated environment. Someone who knows the business helps check the rules and outcomes.

The detailed workflow and case prompts in the repository are there for that later step. They do not need to be completed before the initial data review.

## Sending the first material

One private folder shared with Liam is enough. Group the files by company or platform, use clear names and include a short note explaining what is in the folder. Keep linked IDs and timestamps so the records still connect.

Say what can be shared, anything that has been left out or had names or IDs replaced, and who can help with questions. If an export shows only current values, flag that; information learned later should not be mistaken for what was known at the time.

Once Liam has had a first look, a short walkthrough can help explain the data and narrow down what to explore next. There is no need to pre-select a workflow or prepare a fixed number of cases to get started.
