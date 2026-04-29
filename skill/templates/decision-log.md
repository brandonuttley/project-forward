# Decision Log

A running record of what was decided, by whom, when, and why. Different from a RAID log — this captures choices the team has made, not risks they're managing. The decision log is the artifact that saves you in month four when someone asks "wait, why did we go with vendor X again?"

**When to use:** Any project lasting more than a few weeks, especially one with multiple stakeholders or rotating leadership. Strongly recommended for transformations, vendor implementations, and anything where leadership might change mid-project.

**When NOT to use:** Single-team work where the team's collective memory is sufficient.

**Format default:** xlsx — needs to be filterable and sortable. Markdown works for shorter projects.

---

# [Initiative Name] Decision Log

**Last updated:** [Date]
**Owner:** [Project Lead]

## Why this exists

- Stops the team from re-litigating the same decision every two months
- Onboards new team members faster
- Provides defensibility ("here's why we chose this")
- Forces explicit reasoning at the moment of decision, which leads to better decisions

## The log

| ID | Date | Decision | Made by | Stakeholders consulted | Reasoning | Alternatives considered | Status | Revisit trigger |
|---|---|---|---|---|---|---|---|---|
| D-001 | | [What was decided, in one sentence] | [Decision-maker — name + role] | [Who else weighed in] | [Why this option won] | [What else was on the table and why it lost] | Active / Superseded / Reversed | [What would cause us to reopen this — e.g., "If vendor X misses 30-day milestone"] |
| D-002 | | | | | | | | |
| D-003 | | | | | | | | |

## Decision categories

*Optional — useful for filtering on larger projects.*

- **Scope** — what's in vs. out
- **Technical** — architecture, platform, tooling
- **Vendor / partner** — who we're working with
- **Process** — how we'll run the work
- **Resource / staffing** — who's on the team and how
- **Schedule** — what comes when

## Discipline checklist for each entry

When you record a decision, every entry should pass these tests:

- [ ] **Specific:** "We chose Vendor A for the SaaS integration" — not "We picked our vendor"
- [ ] **Attributed:** Names a specific decision-maker, not "the team"
- [ ] **Reasoned:** Explains *why* in language a new joiner would understand without context
- [ ] **Honest about alternatives:** Names what was rejected and why — "X cost less but couldn't meet our SLA"
- [ ] **Has a revisit trigger:** Names what would cause us to reopen the question

If a decision can't pass these tests, it's either too small to log or hasn't actually been decided.

## When a decision gets reversed

Don't delete the original entry. Mark it "Superseded" or "Reversed" and add a new entry referencing it. The history of *why we changed our minds* is often more valuable than the current decision.

Example:
- D-014 (Superseded): Selected Vendor A based on lower cost. (Reasoning at the time...)
- D-027: Switched to Vendor B. Vendor A failed integration testing in week 4. Vendor B's higher cost is offset by faster implementation.

---

## Notes for the PM

- The decision log is most valuable when *no one is looking for it.* It earns its keep when leadership changes, when a stakeholder questions the approach, or when the team forgets why they ruled something out.
- Pair this with the RAID log. Decisions that resolve risks should reference the risk ID. Risks that emerge from decisions should reference the decision ID.
- For high-stakes decisions, consider a longer "decision memo" attached as a link — but the one-row summary still belongs here.
