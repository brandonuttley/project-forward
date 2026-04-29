# Stakeholder Map

A structured view of who decides, who delivers, who approves, and who needs to be in the loop. Built on a RACI-adjacent model adapted for real cross-functional work — including the often-overlooked "consulted with veto power" category that wrecks projects when handled late.

**When to use:** Before kickoff. Update when sponsors change, scope expands, or a new function (Legal, Compliance, IT Security) enters the picture.

**When NOT to use:** A single-team effort with no external dependencies. RACI is overhead when everyone's in one room.

**Format default:** Markdown for a working session. xlsx if the project is big enough that this will be a living document.

---

# [Initiative Name] Stakeholder Map

**Last updated:** [Date]
**Owner of this document:** [Project Lead]

## How to read this

- **Sponsor:** Funds it. Takes political heat. Has authority to kill it or expand it. Should be exactly one person, ideally with budget authority.
- **Owner / Accountable:** On the hook for delivery. Single point of accountability per workstream. If two people are accountable, no one is.
- **Contributor / Responsible:** Does the work. Multiple people per workstream is fine.
- **Consulted (with veto power):** Has subject-matter authority that can stop the project. Legal, Compliance, Security, Risk, Finance review for material spend. Engage early. They can't be "informed" — they're "consulted."
- **Informed:** Needs updates but doesn't block. Keep the list short or the updates become noise.

## The map

### Sponsor

| Name | Title | Decision rights | Notes |
|---|---|---|---|
| | | Funds the project, breaks ties, owns the business outcome | |

### Owners (Accountable)

| Workstream | Owner | Title | Notes |
|---|---|---|---|
| Overall delivery | | Project Lead | |
| [Workstream 1, e.g., Technical build] | | | |
| [Workstream 2, e.g., Content / creative] | | | |
| [Workstream 3, e.g., Compliance review] | | | |

### Contributors (Responsible)

| Workstream | Contributors | Time commitment | Notes |
|---|---|---|---|
| [Workstream 1] | | | |
| [Workstream 2] | | | |
| [Workstream 3] | | | |

### Consulted (with veto power)

*This is the section most stakeholder maps get wrong. List every function whose review is required and treat them as first-class participants, not late-stage check-ins.*

| Function | Contact | Review trigger | Lead time | Notes |
|---|---|---|---|---|
| Legal | | [What triggers their review — e.g., any external contract] | [Standard SLA, e.g., 5 business days] | |
| Compliance | | [What triggers — e.g., customer comms, regulated content] | | |
| Information Security | | [What triggers — e.g., new vendor with data access, new endpoint] | | |
| Privacy | | [What triggers — e.g., new data collection, new processor] | | |
| Brand / Marketing | | [What triggers — e.g., external creative, public messaging] | | |
| Finance | | [What triggers — e.g., spend over $X, new contract] | | |

### Informed

| Group | Contact | Update frequency | Channel |
|---|---|---|---|
| [e.g., Executive committee] | | Monthly | Steering deck |
| [e.g., Adjacent product team] | | Biweekly | Slack summary |
| [e.g., Customer support leadership] | | Pre-launch | Briefing call |

## Decision rights for common scenarios

*This section forces specificity that abstract RACI doesn't.*

- **Scope change up to [X% / $X]:** Project Lead decides, informs Sponsor.
- **Scope change above that:** Sponsor decides, with input from [Consulted parties].
- **Vendor selection:** [Process — e.g., Project Lead recommends, Sponsor approves with Finance and Procurement sign-off].
- **Launch go/no-go:** [Who decides, based on what criteria].
- **Public communication:** [Comms / Brand approves all external messaging before send].

## Engagement plan for Consulted parties

*The single most common project failure is engaging Legal/Compliance/Security at the eleventh hour. Pre-commit dates.*

| Function | Engagement point 1 | Engagement point 2 | Final review | Notes |
|---|---|---|---|---|
| Legal | [Date — e.g., contract draft] | [Date — e.g., final terms] | [Date — pre-launch] | |
| Compliance | | | | |
| Security | | | | |

---

## Notes for the PM

- If you can't name a single Sponsor, that's a finding — escalate before kickoff.
- If two functions both think they have veto power on the same decision, surface and resolve it now.
- Update this when people change roles. A stakeholder map with the previous compliance lead is worse than no map.
- For regulated environments (financial services, healthcare, etc.), the Consulted section is the most important part. Get it right.
