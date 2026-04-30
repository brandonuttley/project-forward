# Project Forward

**What this is:** A Claude Skill for senior project and program management and marketing project management work. It was inspired by Brandon Uttley's 20+ year career across enterprise transformations, agency leadership, and startup growth — grounded in PMP certification and earlier work in accredited PR practice. See the About Brandon section below for more details.

This is not a chatbot, a prompt library, or a "PM advice" wrapper. It's a working toolkit that produces real artifacts — populated for *your* situation — and surfaces the harder questions before drafting, the way a senior PM would.

---

## How it works

Project Forward turns Claude into a senior PM thinking partner with a working set of templates. When you describe a project you're wrestling with, the skill:

1. **Diagnoses the actual problem** before reaching for a solution. Most "stuck projects" aren't stuck for the reason you think they are.
2. **Challenges your framing**, your unstated assumptions, and the trade-offs you may be ignoring. Like a senior colleague who's caught something you might not want to hear but need to.
3. **Produces real artifacts** — charters, RAID logs, status reports, memos — populated with your specifics, ready to send. Word and Excel formats supported.

The skill is built around a core mental model: every complex initiative is three problems braided together — **the plan, the people, and the message.** Most projects fail on the second two, not the first. The toolkit covers all three.

---

## What's in the skill

The skill ships with **13 templates** for the artifacts a senior PM actually produces, plus core methodology and a routing reference that tells Claude when to use which template.

### Core method

**`SKILL.md`** — The main file. Defines the Project Forward method, conversational pacing rules, the "challenge before solving" rigor discipline, voice and posture guidelines, and routing logic for the templates.

### References

**`references/templates-guide.md`** — Tells Claude when to reach for which template based on the user's situation, and how to handle the markdown-vs-Word-vs-Excel format decision.

**`references/marketing-program-mgmt.md`** — Loaded when the conversation involves marketing program management specifically. Covers the distinction between marketing campaign execution and marketing program management, and how to reposition program-level marketing infrastructure work.

### The 13 templates

| Template | What it is | When to use it |
|---|---|---|
| **`project-charter.md`** | A two-page document that aligns sponsors, owners, and contributors on what the initiative is, what "done" looks like, what's out of scope, and what the sponsor is committing to. | Week one of any cross-functional initiative big enough to span multiple teams or weeks. |
| **`stakeholder-map.md`** | A structured view of who decides, who delivers, who approves, and who needs to be in the loop — including the often-missed "consulted with veto power" category for Legal, Compliance, Security, and Privacy. | Before kickoff. Update whenever sponsors change, scope expands, or a new gating function enters the picture. |
| **`raid-log.md`** | The single most useful artifact for tracking risks, assumptions, issues, and dependencies. Includes scoring discipline, mitigation standards ("monitor" is not a mitigation), and review cadence. | Every project of meaningful complexity. Reviewed weekly, updated continuously. |
| **`decision-log.md`** | A running record of what was decided, by whom, when, and why — with alternatives considered and revisit triggers. Saves you in month four when someone asks "wait, why did we go with vendor X?" | Any project lasting more than a few weeks, especially with multiple stakeholders or rotating leadership. |
| **`pre-mortem.md`** | A structured 60-90 minute working session where the team imagines the project has failed and works backward to identify what killed it. The single best risk-surfacing exercise most teams skip. | Pre-kickoff for any meaningful initiative. Also valuable at major phase boundaries or scope shifts. |
| **`kickoff-agenda.md`** | A structured agenda for the first cross-functional meeting on a complex initiative — built to drive alignment, not generate enthusiasm. Includes pre-read requirements, decision-capture discipline, and explicit next steps. | Beginning of any cross-functional initiative spanning multiple teams or weeks. |
| **`weekly-status.md`** | The standing weekly update to stakeholders. Same format every week, same day every week. Includes honesty checks before sending — am I reporting green when I actually feel yellow? | Standing weekly cadence on any project lasting more than a few weeks. |
| **`scope-change-memo.md`** | The artifact you send to your sponsor when scope, schedule, or budget needs to change. Forces clarity on what's changing, why, and what the sponsor needs to decide. | Any time the project moves outside the bounds set by the charter — material schedule slips, budget overruns, scope additions, resource changes. |
| **`escalation-memo.md`** | When a blocker is outside your authority to resolve, this is the structured ask up the chain. Specific, time-bound, with a clear decision required. | A blocker you've genuinely tried to resolve at your level and can't. A risk that needs executive intervention. |
| **`vendor-rfp-scorecard.md`** | Structured evaluation of vendor proposals against weighted criteria — set *before* seeing the responses, which prevents the all-too-common pattern of rationalizing toward a preferred vendor. | Any vendor selection involving more than two responses, material spend, or strategic implications. |
| **`first-30-days-checklist.md`** | The structured plan for your first month on a project you didn't start. Diagnostic-first, not corrective. Includes challenge questions for the 30-day mark — is the project still solving a real problem, does the sponsor still want this, what's the honest probability of success? | You're new to a project that already exists. Especially valuable when the project is in trouble, the prior PM left, or stakeholders are skeptical. |
| **`marketing-campaign-brief.md`** | A one-to-two page document that defines a marketing campaign before any creative work, media buying, or production starts. The marketing equivalent of a project charter — and the artifact that prevents the most common marketing failure mode. | Before kicking off creative or production for any campaign with material spend, multiple workstreams, or executive visibility. |
| **`resource-capacity-plan.md`** | A structured view of what your team has committed to versus what they can actually deliver. The artifact that prevents silent overcommitment. Especially valuable for marketing program management where multiple campaigns share resources. | Quarterly planning, when new initiatives land, or when "we feel overcommitted" needs to become "here's the math." |

---

## What makes this different from generic AI templates

Most AI-produced PM templates are fluent and forgettable. This skill is built to surface the harder questions before producing artifacts — because senior PM judgment lives in the diagnosis, not the deliverable.

When you ask the skill to draft a charter, it'll first ask whether your success criteria are outcome-based or just activity dressed up as outcome.

When you ask it to write a status report, it'll first ask what you're leaving out because it's politically inconvenient — because that's the entry that matters.

When you state a deadline as fixed, it'll ask whether the date is a real external commitment or an internal aspiration that hardened into a date.

That's the rigor most templates skip.

---

## What it gives you, and what it doesn't

**What it gives you:**
- Structure, rigor, and a head start on the artifacts a senior PM ships
- A diagnostic partner that probes your framing before producing solutions
- Working artifacts populated for your specific situation, ready to send

**What it doesn't give you:**
- The judgment to know when to break the framework
- The political read on which sponsor will actually hold the line
- The communications instinct that turns a tough memo into a signed approval
- Two decades of pattern recognition

That part still requires Brandon. The toolkit covers most teams, most of the time. For the high-stakes moments where judgment matters more than structure, [reach out via brandonuttley.com](https://brandonuttley.com).

---

## Installation

### Option 1: Install in Claude (recommended)

1. Download the **project-forward.skill** file from [Releases](../../releases)
2. In Claude → **Settings → Capabilities → Skills → Upload**
3. Select the downloaded file. Claude will install the skill and have it available for all future conversations.

Once installed, just describe the project you're wrestling with in plain language. The skill will trigger automatically when relevant. You can also explicitly invoke it by asking *"What would Brandon Uttley do?"* or *"Use the Project Forward skill on this."*

### Option 2: Use the templates directly

The templates work fine outside the skill if you'd rather just grab them. Each template in `skill/templates/` is a standalone Markdown file you can copy, adapt, and use however you want.

### Option 3: Browse first

If you want to read the skill files before installing, the bundled plaintext is in [`project-forward.txt`](./project-forward.txt) (about 1,900 lines, optimized for reading on a phone) — or browse the source files in `skill/`.

---

## Repo structure

```
project-forward/
├── README.md                       (you are here)
├── LICENSE                         (MIT)
├── project-forward.skill           (the installable skill package)
├── project-forward.txt             (plaintext bundle for reading)
└── skill/
    ├── SKILL.md                    (main skill file)
    ├── references/
    │   ├── templates-guide.md      (when to use which template)
    │   └── marketing-program-mgmt.md
    └── templates/
        ├── project-charter.md
        ├── stakeholder-map.md
        ├── raid-log.md
        ├── decision-log.md
        ├── pre-mortem.md
        ├── kickoff-agenda.md
        ├── weekly-status.md
        ├── scope-change-memo.md
        ├── escalation-memo.md
        ├── vendor-rfp-scorecard.md
        ├── first-30-days-checklist.md
        ├── marketing-campaign-brief.md
        └── resource-capacity-plan.md
```

---

## Feedback and contributions

If you try the skill and something breaks — or something feels thin, missing, or wrong — please open an issue. The next version gets better because of what users surface. Pull requests welcome for clearer guidance, additional templates, or sharper challenge prompts.

For consulting inquiries or to discuss applying these tools to a real, in-flight situation, reach out via [brandonuttley.com](https://brandonuttley.com).

---

## What this is and isn't

Project Forward produces drafts and frameworks built from professional PM practice. It is not a substitute for domain expertise where the stakes warrant it.

Specifically: in any context where the stakes are regulatory, legal, safety-related, clinical, or financial — where the artifact will be filed with a regulator, used in litigation, relied upon for safety-critical decisions, or carries material business consequence — the skill's output is a starting point for review by qualified professionals. Not a finished document.

The skill's job is to help you think clearly and produce strong drafts faster. The judgment to know when a draft is ready for the moment, and when it needs further expert review, remains yours.

---

## License

MIT. Use it, adapt it, share it. Attribution appreciated but not required.

---

## About Brandon

Brandon Uttley is a Director-level program management and marketing operations leader with 20+ years of experience running complex, high-stakes initiatives across enterprise transformations, agency leadership, and startup growth. His career spans Fortune 500 program management, agency CMO leadership, and co-founding a digital agency he scaled into a nationally recognized firm. He's PMP-certified and formerly APR-accredited, with FEMA Incident Command training and a journalism degree from UNC Chapel Hill. Based in Charlotte, NC.

The work behind this skill: enterprise-scale program coordination in regulated environments, marketing program management at portfolio level, content operations, vendor selection and RFP work, change delivery for tens of thousands of employees, and crisis-grade stakeholder communications.

### Working with Brandon directly

The toolkit covers most teams, most of the time. For situations where judgment matters more than structure — high-stakes transformations, contested executive sponsorship, programs in genuine trouble, or marketing operations needing a serious reset — direct engagement is the right move. Brandon is available for a limited number of advisory engagements each year.

To explore working together, visit [**brandonuttley.com**](https://brandonuttley.com).
