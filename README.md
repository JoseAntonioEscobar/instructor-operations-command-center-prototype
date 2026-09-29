# Instructor Operations Command Center

A functional prototype for managing instructor engagements from intake to completion.

🚀 Live demo:https://joseantonioescobar.github.io/instructor-operations-command-center-prototype/

This project started from a simple operations problem: when a process involves multiple people, handoffs, communication channels and scattered files, it becomes surprisingly easy to lose visibility of what is happening, who owns the next step, and what is blocking progress.

The goal of this prototype is to demonstrate a simple operating model that keeps ownership, actions, deadlines, blockers and evidence visible in one place.

## The Problem

Instructor engagements can involve:

- Agreements and contracts
- Bios, headshots and supporting materials
- Topics and curriculum
- Filming dates and production requirements
- Payments and follow-ups
- Communication through email and WhatsApp
- Tasks managed in different project tools
- Files stored in different locations

When these pieces are distributed across people and tools, common problems appear:

- Unclear ownership
- Missing information
- Forgotten follow-ups
- Stalled handoffs
- Limited visibility for leadership
- Executives spending time chasing status updates

## The Operating Model

The prototype is built around five pieces of information that should always be unambiguous:

**Owner → Next Action → Due Date → Blocker → Evidence**

There is also a simple rule:

> **No vague "waiting" status.**

If something is waiting, the system should make clear:

- What it is waiting for
- Since when
- Who owns the follow-up
- What happens next

The idea is to make the process actionable rather than simply track records.

## Workflow

The prototype organizes engagements into six stages:

1. **Intake & Agreement**
2. **Onboarding**
3. **Content Lock**
4. **Production Ready**
5. **Filmed & Delivered**
6. **Closed**

Each engagement can then be viewed through different operational perspectives.

### Active Engagements
A centralized view of current instructor engagements, including stage, status, owner, next action and due date.

### My Actions
A focused view of actions assigned to the current owner.

### At Risk
A view designed to surface engagements that require attention before they become larger problems.

### Filming This Week
A time-sensitive view for upcoming production activities.

### CEO View
An executive-level view focused on exceptions rather than every operational detail.

The objective is simple:

> Leadership should be able to see what needs attention without having to chase individual updates.

## Automation & AI

The prototype also explores where automation and AI could reduce coordination work.

### Good candidates for automation

- Extracting key information from incoming email / WhatsApp
- Reminders for upcoming deadlines and pending actions
- Detecting stalled engagements
- Handoffs and escalation
- Flagging records that require attention

### Keep with people

Some decisions should remain explicitly owned by people, including:

- Compensation and payments
- Contracts and agreements
- Curriculum and content approval
- Exceptions requiring judgment or context

The principle is:

> **Automation should remove coordination work, not accountability.**

## From Prototype to Implementation

This is intentionally a **conceptual functional prototype**, not a production system.

The intended progression would be:

**Case Study → Operating Model → Working Prototype → Airtable Implementation → Automations, Integrations & Governance**

A production implementation could use Airtable as the system of record, with the appropriate views, automations and integrations layered around the operating model.

The prototype exists to make the operating model tangible before implementing it in a production environment.

## Why Build a Prototype First?

The goal was not to build another dashboard simply because a dashboard was possible.

The prototype was created to answer a more practical question:

> **Does the proposed operating model actually make the process easier to understand and operate?**

Building the interface first makes it possible to test the workflow, identify missing information and discuss the model before committing to a production implementation.

## Project Status

**Status:** Functional prototype  
**Data:** Mock data  
**Integrations:** Not connected  
**Production system:** Not implemented

This project is intended as a demonstration of operational thinking, workflow design, automation opportunities and AI-assisted process improvement.

## Tech

- HTML
- CSS
- JavaScript
- Mock operational data
- Responsive UI

No backend or external integrations are required to explore the prototype.

## Demo

Open `index.html` locally in a browser to explore the prototype.

---

### Author

**José Antonio Escobar**  
Operations & Supply Chain

This project was created as an independent exploration of an operations case study and is not an implementation of any company's internal system.
