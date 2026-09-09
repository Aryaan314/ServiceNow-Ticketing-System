# ServiceNow ITSM Portfolio

Hands-on practice project built in a personal ServiceNow Developer Instance to build real, demonstrable skills in IT service management, ticketing workflows, and help desk support — as a complement to my Google IT Support Professional Certificate.

This project covers the full incident lifecycle, service catalog requests, knowledge management, root cause analysis (Problem Management), change management, and reporting/analytics.

---

## Table of Contents
- [Incident Management](#incident-management)
- [Service Catalog Requests](#service-catalog-requests)
- [Knowledge Base](#knowledge-base)
- [Problem Management](#problem-management)
- [Change Management](#change-management)
- [Reporting & Analytics](#reporting--analytics)
- [Skills Demonstrated](#skills-demonstrated)

---

## Incident Management

Logged, triaged, and resolved multiple Tier 1 and Tier 2 incidents following standard ITIL fields (impact, urgency, priority) with full documentation at every stage — from intake through work notes to resolution.

**Tickets handled:**
| Ticket | Issue | Category | Priority |
|---|---|---|---|
| INC0010006 | Password expired, unable to log in | Software | 3 - Moderate |
| INC0010007 | Office printer offline | Hardware | 4 - Low |
| INC0010008 | Laptop running slow | Hardware | 5 - Planning |
| INC0010009 | Outlook not syncing new emails | Software | 3 - Moderate |
| INC0010010–12 | Recurring WiFi drops (3 linked incidents) | Network | 1 - Critical |

Each ticket followed the full lifecycle: **New → In Progress (with documented troubleshooting) → Resolved**, with resolution codes and notes appropriate to the fix applied.

**Screenshots:**
- `01-incident-inc0010006-new.png` — New ticket intake (password reset)
- `02-incident-inc0010006-queue.png` — Ticket queue/list view
- `03-incident-inc0010006-inprogress.png` — Work notes documenting troubleshooting
- `04-incident-inc0010006-resolved.png` — Full resolution with notes
- `05-incident-inc0010007-queue.png` — Queue view (printer ticket)
- `06-incident-inc0010007-inprogress.png` — Work notes (printer troubleshooting)
- `07-incident-inc0010007-resolved.png` — Resolved (printer)
- `08-incident-inc0010008-queue.png` — Queue view (slow laptop ticket)
- `09-incident-inc0010008-inprogress.png` — Work notes (disk cleanup, startup items)
- `10-incident-inc0010008-resolved.png` — Resolved (slow laptop)
- `11-incident-inc0010009-queue.png` — Queue view (email sync ticket)
- `12-incident-inc0010009-inprogress.png` — Work notes (Outlook profile repair)
- `13-incident-inc0010009-resolved.png` — Resolved (email sync)
- `22-incident-inc0010010-resolved-linked.png` — Resolved WiFi incident, referencing the linked Problem and Change records (see below)

---

## Service Catalog Requests

Submitted a request through the employee-facing Service Catalog, demonstrating the self-service side of ITSM (separate from the agent-facing Incident workflow).

- **Request:** Adobe Acrobat Pro (REQ0010001)
- Shows the distinction between an **Incident** (something broken) and a **Request** (something needed) — two different record types with their own fulfillment tracking.

**Screenshot:**
- `14-service-catalog-request-confirmation.png` — Order confirmation with fulfillment stage tracker

---

## Knowledge Base

Authored 3 knowledge articles based on resolved incidents, turning one-off fixes into reusable documentation for future agents and self-service users.

1. **How to Fix a Password Expiration Login Issue**
2. **Troubleshooting a Printer Showing Offline**
3. **Fixing Outlook Email Sync Issues**

Each article follows a consistent structure: Problem, Steps to Resolve, Prevention Tip.

**Screenshots:**
- `15-kb-article-password-reset.png`
- `16-kb-article-printer-offline.png`
- `17-kb-article-email-sync.png`

---

## Problem Management

Built a full root cause investigation for a recurring issue affecting multiple users, demonstrating the difference between treating symptoms (incidents) and fixing root causes (problems).

**Scenario:** Three separate incidents (INC0010010, INC0010011, INC0010012) reported by different users all pointed to the same underlying issue — an overloaded 2nd floor wireless access point.

- **Problem record:** PRB0040001
- **Linked incidents:** 3, all traced to a single root cause
- **Workaround documented:** Temporary mitigation (5GHz/ethernet fallback) while a permanent fix was planned
- **Root cause documented:** Access point overloaded during peak hours
- **Full stage progression:** New → Assess → Root Cause Analysis → Fix in Progress → Resolved

**Screenshots:**
- `18-problem-linked-incidents.png` — Problem record with all 3 linked incidents (key screenshot)
- `19-problem-root-cause-analysis.png` — Workaround and cause notes documented
- `23-problem-resolved-full-lifecycle.png` — Final resolved state with full stage tracker, every stage checked off

---

## Change Management

Created a formal Change Request tied to the Problem above, demonstrating the ITIL Incident → Problem → Change pipeline in full.

- **Change Request:** CHG0030001 — "Replace overloaded 2nd floor wireless access point"
- **Type:** Normal Change (planned, non-emergency)
- **Risk:** Moderate
- Full planning documentation: **Justification, Implementation Plan, Risk & Impact Analysis, Backout Plan, Test Plan**
- Change moved through the approval workflow (New → Assess, awaiting formal approval)

**Screenshots:**
- `20-change-request-planning.png` — Full change documentation
- `21-change-request-approval-pending.png` — Change awaiting approval, showing a realistic governance gate

This scenario shows the complete chain: **3 related incidents → 1 root-caused problem → 1 formally planned and risk-assessed change**, with every record referencing the others in its notes.

---

## Reporting & Analytics

Built reports to visualize ticket data — a core skill for help desk roles that involve tracking team performance and identifying trends.

1. **Incidents by Category** (pie chart) — breakdown of ticket volume by Hardware, Software, Network, etc.
2. **Incidents by Priority, stacked by Category** (bar chart) — shows both urgency distribution and what kinds of issues make up each priority tier

**Screenshots:**
- `24-report-incidents-by-category.png`
- `25-report-incidents-by-priority-stacked.png`

---

## Skills Demonstrated

- Incident lifecycle management (intake, triage, troubleshooting documentation, resolution)
- ITIL priority/impact/urgency matrices
- Service Catalog request fulfillment
- Knowledge-centered service (KCS) article authoring
- Problem management and root cause analysis
- Change management with risk assessment and backout planning
- Ticket reporting and data visualization
- End-to-end ITSM process thinking (how incidents, problems, changes, and requests relate to one another)

---

*Built in a ServiceNow Personal Developer Instance for self-directed learning and portfolio purposes.*
