# RAID Log

Risks, Assumptions, Issues, and Dependencies. The single most useful artifact for keeping a project honest about what could go wrong, what we're betting on, what's already gone wrong, and what we need from others. A well-run RAID log is a project's nervous system.

**When to use:** Every project of meaningful complexity, from kickoff to closeout. Reviewed weekly. Updated continuously.

**When NOT to use:** Tiny efforts where the risks fit in your head. If the RAID log has zero entries after week two, the project's either trivial or someone's not paying attention.

**Format default:** xlsx — this is fundamentally tabular, gets filtered and sorted, multiple people update it. Markdown works for the initial draft or a small project.

---

# [Initiative Name] RAID Log

**Last updated:** [Date]
**Owner:** [Project Lead]

## Definitions

- **Risk:** Something that *might* happen and would hurt the project if it did. Has probability and impact.
- **Assumption:** Something we're treating as true without proving it. If wrong, the plan changes. Test the load-bearing ones early.
- **Issue:** Something that *has* happened and is currently affecting the project. A risk that came true is now an issue.
- **Dependency:** Something we need from outside the team to deliver. Time-bound. Owned externally.

## Risks

| ID | Risk | Probability (H/M/L) | Impact (H/M/L) | Score | Owner | Mitigation | Status | Last reviewed |
|---|---|---|---|---|---|---|---|---|
| R-001 | [Specific risk — not "people might be busy" but "Compliance has a 4-week backlog in Q4 that could push our review past launch"] | H | H | 9 | [Name] | [Specific mitigation, not "monitor closely"] | Active / Mitigated / Closed | |
| R-002 | | | | | | | | |
| R-003 | | | | | | | | |

**Scoring:** H=3, M=2, L=1. Multiply for total. Anything 6+ deserves explicit attention each week.

**Mitigation discipline:** A mitigation that says "monitor" is not a mitigation. A mitigation that says "engage Compliance lead by Aug 15 to get on Q4 schedule" is.

## Assumptions

| ID | Assumption | If wrong, consequence | Validation plan | Validated? | Owner |
|---|---|---|---|---|---|
| A-001 | [e.g., "Legal review of vendor contract takes 5 business days based on prior projects"] | [e.g., "Launch slips by 2-3 weeks"] | [e.g., "Confirm with Legal lead by 7/10"] | Y/N | |
| A-002 | | | | | |
| A-003 | | | | | |

**Discipline:** The most dangerous assumptions are the ones you don't notice you're making. Force yourself to write them down.

## Issues

| ID | Issue | Date raised | Impact | Owner | Action plan | Target resolution | Status |
|---|---|---|---|---|---|---|---|
| I-001 | [What happened, factually] | | [Concrete impact on schedule, scope, or cost] | | [Specific next steps] | | Open / In progress / Resolved |
| I-002 | | | | | | | |

**Issues vs. risks:** An issue is a risk that happened. Move it from the Risks tab to the Issues tab when it materializes.

## Dependencies

| ID | What we need | From whom | By when | Owner on our side | Status | Notes |
|---|---|---|---|---|---|---|
| D-001 | [Specific deliverable — not "their input" but "approved security architecture review"] | [Person/team] | [Date] | [Our PM contact] | On track / At risk / Late | |
| D-002 | | | | | | |
| D-003 | | | | | | |

**Discipline:** Dependencies are the biggest source of project slippage and the easiest to underestimate. Treat them like miniature projects — track lead time, escalate early, write down what you've requested.

---

## How to use this log

1. **Review weekly.** Top of the standing project meeting. Every entry gets eyeballed. Stale entries either resolve or escalate.
2. **Color-code or filter.** In xlsx, filter by Status = Active. Sort risks by score. Surface the top 3-5 each week to the steering committee.
3. **Don't hide.** RAID logs that only contain "green" entries are PR documents, not management tools. If it's red, write it red.
4. **Link to artifacts.** Every entry should connect to action — a meeting, an email, an updated plan. A RAID log with no follow-through is theater.

## Notes for the PM

- The first version of this log will be incomplete. Update it weekly and it becomes accurate by week three.
- Risks that never close are usually either over-stated (too vague) or under-managed (no real owner). Diagnose which.
- The single best risk-surfacing exercise is a pre-mortem at kickoff. See `pre-mortem.md`.
