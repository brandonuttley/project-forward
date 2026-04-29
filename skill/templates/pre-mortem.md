# Pre-Mortem Worksheet

The single best risk-surfacing exercise most teams skip. Imagine the project has failed catastrophically. Work backward from that failure to identify what killed it. Run before kickoff or at any inflection point where the path forward feels uncertain.

**When to use:** Pre-kickoff for any meaningful initiative. Also valuable at major phase boundaries, vendor selection moments, or when a project shifts scope significantly.

**When NOT to use:** When you've already done one for this project recently and nothing has changed. Also skip if the team is in active crisis — pre-mortems work in calm, post-mortems work in crisis.

**Format default:** Markdown for the working session — this is meant to be filled in collaboratively, not circulated. Convert outputs into RAID log entries afterward.

---

# [Initiative Name] Pre-Mortem

**Date:** [Working session date]
**Facilitator:** [Project Lead or PM]
**Participants:** [Who's in the room — ideally 4-8 people across functions]
**Time required:** 60-90 minutes

## The setup (read aloud at the start)

"It's [target completion date]. The project has failed. Not just missed a milestone — actually failed. Leadership is asking what went wrong. Internal stakeholders are frustrated. The team is demoralized.

For the next 15 minutes, working individually, write down everything that could have caused this failure. Be specific. Don't self-censor. The point is to surface risks now, while we can still do something about them."

## Step 1: Silent individual writing (15 min)

Each participant writes their own list. No discussion yet. This prevents anchoring on the loudest voice.

| # | What killed the project (one item per row) |
|---|---|
| 1 | |
| 2 | |
| 3 | |
| 4 | |
| 5 | |
| 6 | |
| 7 | |
| 8 | |
| 9 | |
| 10 | |

## Step 2: Round-robin sharing (20 min)

Each participant reads one item at a time, going around the room. Add to a shared list. Cluster similar items as you go. No debate yet — just capture.

**Master list of failure modes:**

| ID | Failure mode | Cluster (e.g., "Stakeholder," "Technical," "Resource") | Raised by |
|---|---|---|---|
| F-001 | | | |
| F-002 | | | |
| F-003 | | | |
| F-004 | | | |
| F-005 | | | |
| F-006 | | | |
| F-007 | | | |
| F-008 | | | |

## Step 3: Probability and impact (15 min)

Score each failure mode on probability (will this actually happen?) and impact (if it does, how bad?). Use H/M/L. Sort by combined score.

| ID | Failure mode | Probability | Impact | Combined |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

## Step 4: For the top 5 — what would prevent it? (20 min)

Now switch from diagnostic to prescriptive. For each top-scored failure mode, name a specific mitigation that costs less than the failure would.

| ID | Top failure mode | Specific mitigation | Owner | By when |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |
| | | | | |
| | | | | |

**Mitigation discipline:** "Communicate better" is not a mitigation. "Schedule biweekly Legal review starting Aug 1 to avoid the Q4 backlog" is. If it's not specific, it won't happen.

## Step 5: Update the RAID log (after the session)

Take the top failure modes and translate them into RAID log entries. The pre-mortem outputs feed the RAID log directly — that's where the ongoing tracking lives.

---

## Common failure modes to seed thinking

If the team is having trouble generating items, these prompts often unlock:

**People failures:**
- The sponsor disengaged or left the company
- A key stakeholder felt blindsided and dug in
- The team lost a critical contributor mid-project
- We never had real authority to make decisions we needed to make

**Plan failures:**
- We discovered a dependency we didn't know existed
- The original timeline was wishful thinking
- Scope crept and no one said no
- We solved the wrong problem brilliantly

**Message failures:**
- Leadership heard about a problem from someone other than us
- Customers/employees learned about the change from a leak or rumor
- Two stakeholders had different understandings of what "done" meant
- We declared victory based on metrics that didn't reflect actual outcomes

**External failures:**
- A vendor missed a critical milestone
- A regulator or compliance body rejected the approach late
- Market conditions changed mid-flight
- A higher-priority initiative pulled resources away

## Notes for the PM / facilitator

- The hardest part is keeping people in failure mode for 15 minutes. They'll want to immediately problem-solve. Don't let them.
- The most valuable items often come from the most junior people in the room. Senior folks have learned to self-edit. Make space.
- A pre-mortem that produces no surprises is suspicious. Either the team is too aligned (groupthink) or hasn't been honest. Push.
- This works because it gives people social permission to name uncomfortable truths. The framing matters: "the project failed" is psychologically different from "what could go wrong?"
