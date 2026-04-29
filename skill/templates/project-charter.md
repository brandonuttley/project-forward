# Project Charter

A one-page document that aligns sponsors, owners, and contributors on what this initiative actually is — before anyone writes a single line of code or a single creative brief. The charter is the answer to "what are we doing and why" in a form that can be signed off in writing.

**When to use:** Week one of any new initiative big enough to span multiple teams, multiple weeks, or multiple sign-offs. Smaller efforts can skip it. Larger efforts skip it at their peril.

**When NOT to use:** A single-team, single-sprint deliverable. A charter for a two-day task is overhead. Use a one-line description in a ticket instead.

**Format default:** docx for distribution and sign-off. Markdown if it's an internal working draft.

---

# [Initiative Name] Project Charter

**Sponsor:** [Name, title — the executive who funds this and takes the heat]
**Project Lead:** [Name, title — accountable for delivery]
**Date:** [Charter date]
**Status:** Draft / Review / Signed Off
**Version:** 0.1

## 1. Why we're doing this

*One paragraph. The business reason. What changes for the company, customer, or operation if this succeeds. Avoid jargon. If you can't write this in plain English, the project isn't ready.*

## 2. What "done" looks like

*Specific, observable success criteria. Not "we launched X" — but "X is live, Y people use it weekly, Z metric moved by W%." Three to five criteria. If you can't measure it, find a proxy you can.*

- [Outcome 1, with metric]
- [Outcome 2, with metric]
- [Outcome 3, with metric]

## 3. What we're NOT doing

*Just as important as scope. What's explicitly out of scope. The thing that's "obviously next" but not part of this initiative. The feature the loudest stakeholder will ask for in week three. Name it now.*

- [Out-of-scope item 1]
- [Out-of-scope item 2]
- [Out-of-scope item 3]

## 4. Key milestones

| Milestone | Target date | Owner |
|---|---|---|
| Charter signed | | |
| Kickoff complete | | |
| [Major dependency met] | | |
| [Phase 1 delivery] | | |
| [Beta / soft launch] | | |
| Launch | | |

*Don't fake precision. If you don't know a date, write "TBD by [trigger]" — e.g., "TBD by vendor selection."*

## 5. Budget and resources

- **Total budget:** $[amount] (or "TBD pending finance approval")
- **Team commitment:** [N] FTEs / [hours/week] across the duration
- **Key external resources:** [vendors, agencies, contractors]

## 6. Sponsor commitments

*This is the part most charters skip and shouldn't. The sponsor signs the charter — these are what they're agreeing to.*

The sponsor commits to:
- Decision turnaround within [N] business days on escalations
- Standing weekly check-in (or biweekly, depending on duration)
- Resolving cross-functional conflicts that the project lead can't unblock
- Communicating scope changes to leadership before they reach the team

## 7. Top three risks

*Not the full RAID log. The top three things that could kill this. Force the prioritization now.*

1. **[Risk]:** [Why it matters and what would mitigate it]
2. **[Risk]:** [Why it matters and what would mitigate it]
3. **[Risk]:** [Why it matters and what would mitigate it]

## 8. Stakeholders

*Brief — full mapping lives in the stakeholder map.*

- **Sponsor:** [Name]
- **Owners:** [Names — accountable for delivery]
- **Consulted (with veto power):** [Legal, Compliance, Security, etc.]
- **Informed:** [Departments / leaders kept in the loop]

## 9. How we'll communicate

- **Weekly status:** [Format, audience, day]
- **Steering review:** [Cadence, attendees]
- **Escalation path:** [Project Lead → Sponsor → ?]
- **Working channel:** [Slack channel, Teams, etc.]

---

**Sign-offs**

| Role | Name | Date |
|---|---|---|
| Sponsor | | |
| Project Lead | | |
| [Other key approver] | | |

---

## Notes for the PM (delete before sending)

- A charter that doesn't get signed is a charter that doesn't bind anyone. Push for the actual signature.
- If a sponsor refuses to commit to the items in section 6, that's a finding. Surface it before kickoff.
- Update the charter when scope changes. A stale charter is worse than no charter.
- If you can't fit this on two pages, you're padding. Cut.

## Challenge questions to ask before submitting

Before sending the charter for sign-off, run it through these. If you can't answer them, the charter isn't ready.

- **Is the success criteria outcome-based or activity-based?** "We launched the platform" is activity. "5,000 active users by Q3 with NPS above 40" is outcome. If your section 2 is mostly activities, rewrite it.
- **Is the sponsor a real sponsor, or a name you put in the box?** A real sponsor will personally weigh in on the trade-offs, fight for resources, and take political heat. If yours won't, name a different sponsor or escalate the gap.
- **What's the sponsor's actual stake in this succeeding?** If the answer is "they were assigned this," that's a yellow flag. Sponsors with no skin in the game disengage when things get hard.
- **Did you list things as out-of-scope that nobody is asking to add, just to fill the box?** The out-of-scope list earns its keep when it includes things the loudest stakeholder will ask for in week three. If it doesn't, you haven't thought about it hard enough.
- **Is the timeline based on a real external commitment, or an internal aspiration?** "Launch by Q2" because of a regulatory deadline is different from "Launch by Q2" because someone said it in a meeting. Be honest about which.
- **If this project failed, what's the most likely reason?** If you can't answer this in one sentence, run a pre-mortem before kickoff.
