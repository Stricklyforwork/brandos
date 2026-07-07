# Brands OS — Interactive Mockup

A clickable, single-file mockup of **Brands OS**: the internal command center for
managing every brand, campaign, content plan, task, offer, asset, and operational
priority across GHL Brands.

Open `index.html` in any browser — no build step, no dependencies, fully self-contained.

## The core idea

**One record, many views.** A task exists once, with fields (Brand, Campaign, Type,
Owner, Status, Due, Priority), and automatically appears in every relevant view:
its Brand HQ, its campaign, its owner's workload, the Today view, and the Master
Command Center. Nothing is duplicated.

Each brand gets its own HQ; the parent company gets one summarized command center.

## What the mockup covers

Navigation is deliberately small — nine top-level items; sections that hold
several pages get a secondary tab strip under the top bar.

| Rail item | Pages |
|---|---|
| Command Center | Overview (incl. sales movement + pipeline by stage), Today, Needs Attention, Inbox |
| Brands | Directory → Brand HQ (Overview, BrandIQ w/ competitors, Sales, Products, Campaigns, Content, Social, Tasks, Assets, Reports) |
| Tasks | Master task list with saved-view filters; Signoffs (internal vs client approval requests with approve/nudge actions); Lists (shared info, deliberately not tasks) |
| Campaigns | Stats, Board / Timeline (Gantt) toggle, playbooks, and deep detail for a Live and a Building campaign (funnel conversion, email sequence results, launch checklist, tasks, performance vs goal, notes); board cards link to their detail |
| Content | Pipeline board + item detail (repurposing tracker, approval trail), Social Calendar |
| Sales | Pipeline (deal stages w/ values), Products & Services (MRR, product record), Transactions (ledger + billing status), Competition (competitor records, positioning, watchlist) |
| Business | CRM Light (contacts/prospects/partners), Clients (project-phase tracking per client with a phase-timeline + deliverables detail view), Support |
| Library | Assets, Notes & Decisions |
| Reports | Brand health, content output, workload, revenue |
| System | Automations (text-to-automate composer with approval gate + active rules), Settings/Roles |

Universal Quick Add (what / brand / owner / due / related) is available everywhere.

Deliberately **not** in V1 (per the product definition): direct social publishing,
full CRM replacement, deep HighLevel sync, client portal, AI agents running
automations.

## Notes

- Light and dark themes (follows OS preference; token-driven CSS).
- All data is sample/mock data.
- Brand HQ is fully populated for GHL Social; other brands swap the header and
  show sample data, marked as such.
