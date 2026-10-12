---
title: "LabHacker Maceió: free-software management system with Odoo"
kicker: "Consulting · October 2026 – January 2027"
lede: "Implementation of a Portuguese-language, open-source management system for a Brazilian digital-culture laboratory, plus fundraising consulting."
date: "2026-10-01"
categories:
  - "consulting"
coverImage: "cover-labhacker.svg"
description: "Odoo implementation consulting for LabHacker, the Brazilian Laboratory of Digital Culture in Maceió: open-source ERP, custom modules for minutes, approvals, expenses, contracts and fundraising."
---

<dl class="facts">
  <div><span class="k">Client</span><span class="v">LabHacker, Maceió (AL)</span></div>
  <div><span class="k">Service</span><span class="v">Odoo implementation + fundraising consulting</span></div>
  <div><span class="k">Period</span><span class="v">Oct 2026 – Jan 2027</span></div>
  <div><span class="k">Stack</span><span class="v">Odoo 19 Community · OCA · PostgreSQL · Docker</span></div>
</dl>

LabHacker is the Brazilian Laboratory of Digital Culture, a civil-society organisation working in digital culture. Its team runs projects, events, courses and a shop, and needed one place for minutes, approvals, reimbursements, contracts and fundraising, without paying per-user licences or depending on a proprietary vendor.

My proposal was a **free-software management system in Portuguese**, built on Odoo Community and the Odoo Community Association (OCA) modules, with custom development only where nothing existed.

## What the engagement covers

- **Needs workshop and module map.** Each need raised by the team was mapped to a native Odoo app, an OCA module, a custom module or a second phase, so that scope stayed honest about what the free edition does and does not include.
- **Server and security.** Odoo 19 in containers, automatic HTTPS, daily backups with retention, closed public sign-up, role-based access (board, coordination, finance, communication, staff, externals) and a closed, invitation-only sign-up.
- **Brazilian non-profit accounting.** A chart of accounts for non-profits following ITG 2002, with withholding-tax rules, bank reconciliation and fixed-asset depreciation from OCA.
- **Custom modules**, each built as a lean first version the team actually uses:
  - *Minutes*: decisions become tasks with owner and deadline, and people are notified by e-mail and chat
  - *Approvals*: a single queue for communication, purchases and contracts
  - *Batch expenses with OCR*: upload receipts, review, send for approval
  - *Contracts* with parties, value, term and expiry alerts
  - *Fundraising CRM*: funder, amount requested, counterpart, deadlines, reporting duties
  - *Travel requests* with compared quotes
  - *Attendance*: time recording rules adapted for a non-profit team
- **Documentation.** A 41-page user manual inside the system's own knowledge base, written for non-technical staff.
- **Fundraising consulting**, running alongside the implementation, so that the new CRM and the lab's funding strategy are built together.

## Approach

Open source by default, small increments, and documentation as a deliverable. The system is designed so that LabHacker can keep, host, audit and extend it without me.

[LabHacker](https://labhacker.org.br) · [Back to Consulting](/consulting.html)
