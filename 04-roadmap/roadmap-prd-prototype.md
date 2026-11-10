# Roadmap, PRD & Prototype

> **Module 4 · ★ Deliverable 4.** Repo file `04-roadmap/roadmap-prd-prototype.md` — part of your submission.
> Do the lab in the **Module 4 · Exercise 1 Guide** (linked from the Module 4 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Roadmap, PRD & Prototype** slide of your Module 6 final deck. (Your Module 4 · Exercise 2 PRD sprint lands in `prd-and-prototype.md`.)


# Feature Roadmap, Module 4 · RouteLogic Velocity

**Team:** 2 engineers + 1 designer + 1 CS lead

## Strategic anchors
- **Persona:** Frontline Dispatcher / Logistics Coordinator responsible for coordinating daily deliveries, managing route changes, and monitoring driver progress.
- **Primary metric:** Reduce average daily coordinator time spent on manual workarounds by ~20%, from 31 minutes to ≤25 minutes/day.
- **Moment of misery:** Delayed statuses and route reassignments force coordinators to chase drivers through calls, texts, and WhatsApp, then manually reconcile responses with Velocity.
- **Guardrail:** Manager Reporting CSAT must remain ≥4.5/5, ensuring frontline simplification does not weaken existing administrative reporting value.

## Scoring
| Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|
| B1 One-Click Compliance Checklist | 5 | 3 | Major Project | Now | Directly attacks the biggest measured bottleneck: compliance takes 14.6 min vs. 3 min benchmark. |
| B2 Smart Daily Report Auto-Fill | 4 | 4 | Major Project | Next | Reporting takes 9.7 min vs. 3 min, but AI auto-fill introduces more implementation and validation complexity. |
| B3 Shift Handoff Wizard | 4 | 3 | Major Project | Now | Directly targets the 6.8-minute handoff gap and reduces manual coordinator effort. |
| B4 Mobile-First Coordinator Dashboard | 4 | 4 | Major Project | Next | Strong persona fit, but a broader dashboard redesign is too large for the focused four-week pilot. |
| B5 Step Progress Indicator | 3 | 1 | Fill-In | Now | Low-effort improvement supporting workflow completion while B1/B3 address the substantive friction. |
| B6 Driver Alert Notifications | 3 | 3 | Time Sinker | Next | Addresses M2 communication pain, but notifications alone do not resolve synchronization delays or confirm acknowledgment. |
| B7 Contextual AI ETA Display | 2 | 4 | Time Sinker | Cut | Weak connection to workaround time and poor frontline adoption make AI ETAs a poor pilot investment. |
| B8 Fleet Analytics Manager View | 1 | 4 | Time Sinker | Cut | Sales-driven manager functionality does not address coordinator friction or move the primary metric. |
| B9 Compliance Audit Trail Export | 2 | 3 | Time Sinker | Later | Potential regulatory value, but does not reduce the coordinator's compliance task time. |
| B10 In-App Coordinator Training | 2 | 2 | Fill-In | Later | Training could support adoption, but teaches users around workflow friction rather than removing it. |

## Roadmap
### NOW, Pilot (4 weeks, 3 accounts)
- **B1 One-Click Compliance Checklist**, Directly attacks the biggest measured bottleneck: compliance takes 14.6 min vs. 3 min benchmark.
- **B3 Shift Handoff Wizard**, Directly targets the 6.8-minute handoff gap and reduces manual coordinator effort.
- **B5 Step Progress Indicator**, Low-effort improvement supporting workflow completion while B1/B3 address the substantive friction.

### NEXT, GA Release (weeks 5-8)
- **B2 Smart Daily Report Auto-Fill**, Reporting takes 9.7 min vs. 3 min, but AI auto-fill introduces more implementation and validation complexity.
- **B4 Mobile-First Coordinator Dashboard**, Strong persona fit, but a broader dashboard redesign is too large for the focused four-week pilot.
- **B6 Driver Alert Notifications**, Addresses M2 communication pain, but notifications alone do not resolve synchronization delays or confirm acknowledgment.

### LATER, backlog
- **B9 Compliance Audit Trail Export**, Potential regulatory value, but does not reduce the coordinator's compliance task time.
- **B10 In-App Coordinator Training**, Training could support adoption, but teaches users around workflow friction rather than removing it.

### ✂ Cut List
- **B7 Contextual AI ETA Display**, Weak connection to workaround time and poor frontline adoption make AI ETAs a poor pilot investment.
- **B8 Fleet Analytics Manager View**, Sales-driven manager functionality does not address coordinator friction or move the primary metric.
