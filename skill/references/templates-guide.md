# Templates Guide

When the conversation reaches a point where a real artifact would help the user, **produce one**. This guide tells you which template to reach for, how to populate it, and whether to deliver it as markdown or as a downloadable Word/Excel file.

## The core principle

Templates are scaffolding, not the answer. A blank charter template doesn't help anyone. A charter populated with the user's specific initiative, sponsor, success criteria, and risks — that's an artifact they can actually send.

When you produce from a template:
1. **Populate every placeholder** with content drawn from the conversation. Don't leave `[TBD]` fields without explicitly flagging them as user input needed.
2. **Cut sections that don't apply.** A vendor scorecard for a small purchase doesn't need 12 weighted criteria. A charter for a 3-week project doesn't need a quarterly milestone plan.
3. **Surface assumptions.** Every artifact you generate from limited information makes assumptions. Name them at the top so the user can correct them: "Assumed: launch date is Q2 EOQ, sponsor is VP of Product. Correct me if not."
4. **Don't pad.** If a section needs three bullets, write three bullets. Don't pad to seven for symmetry.

## Markdown vs. Word vs. Excel

The default is markdown — fast to produce, easy to iterate on, copy-pasteable into anything. Move to Word or Excel only when one of these triggers applies:

**Use docx (Word) when:**
- The user explicitly asks for a Word doc, downloadable file, or "something I can send"
- The artifact will be circulated for executive review or formal sign-off
- The artifact will live in a document repository (SharePoint, Confluence with Word attachments, etc.)
- It's a memo, charter, brief, or formal communication

Read `/mnt/skills/public/docx/SKILL.md` before generating any docx file.

**Use xlsx (Excel) when:**
- The artifact is fundamentally tabular and will be filtered, sorted, or updated over time
- Multiple people will edit it
- It contains scoring, calculations, or data that benefits from formulas
- The user mentions tracking, dashboard, or "rolling" updates

Read `/mnt/skills/public/xlsx/SKILL.md` before generating any xlsx file.

**Templates that are usually best as xlsx:** RAID log, decision log, vendor RFP scorecard, resource/capacity plan, first-30-days checklist (if being tracked).

**Templates that are usually best as docx:** project charter, scope-change memo, escalation memo, kickoff agenda, weekly status report, marketing campaign brief.

**Pre-mortem and stakeholder map** can go either way — pre-mortem is often faster as markdown for a working session; stakeholder map works as either depending on whether it's a one-time exercise (markdown) or a living document (xlsx).

When in doubt, ask: "Want this as markdown for quick reference, or a Word/Excel file you can send?"

## Choosing the right template for the moment

The conversation usually reveals which template fits. Here's how to read it:

| User signal | Template to reach for |
|---|---|
| "I'm starting a new [initiative]" | `project-charter.md` |
| "Who needs to approve this?" / "I don't know who decides" | `stakeholder-map.md` |
| "What could go wrong?" / "How do I track risks?" | `raid-log.md` |
| "We keep re-deciding the same thing" / "Why did we choose X again?" | `decision-log.md` |
| "I'm worried about this project" / "Help me think through the risks" | `pre-mortem.md` |
| "I have a kickoff next week" | `kickoff-agenda.md` |
| "I need to send a status update" / "How's it going report" | `weekly-status.md` |
| "We need to add scope" / "The deadline is slipping" | `scope-change-memo.md` |
| "I need help getting [VP/SVP] involved" / "This is blocked" | `escalation-memo.md` |
| "We're choosing between vendors" / "RFP responses came in" | `vendor-rfp-scorecard.md` |
| "I just took over this project" / "It's a mess and I'm new" | `first-30-days-checklist.md` |
| "I need to brief the team on [campaign]" / "Marketing wants to launch X" | `marketing-campaign-brief.md` |
| "We're overcommitted" / "Can we actually do all this?" | `resource-capacity-plan.md` |

If the user's situation calls for two or three templates, offer them as a sequence rather than dumping all of them at once. Example: "For week one, I'd start with a charter and a stakeholder map. The RAID log can come after the kickoff. Want me to draft the charter first?"

## When NOT to produce a template

Don't reach for a template when:

- The user is venting and needs to think out loud first
- The actual problem is interpersonal (a difficult sponsor, a turf war), not documentational
- The user's situation is too ambiguous to populate the template responsibly — ask one or two clarifying questions instead
- The user explicitly says they want thinking, not artifacts
- **The conversation has barely started.** A user who's said one or two sentences hasn't given you enough to populate any template well. Ask first, draft later.

Templates are powerful because they're concrete. That same concreteness is wrong for moments that need diagnosis, not delivery.

## Pacing — earn the right to draft

Even when a template is clearly the right artifact, the skill works best when it *earns* the moment to produce one. Pattern:

1. **First response:** short framing + one clarifying question. No artifact offer yet.
2. **After the user answers:** confirm the diagnosis, ask one more question if needed, *then* offer the artifact. "Sounds like the issue is X. I can draft a charter that names Y as the success criterion and forces the sponsor to commit to Z. Want me to?"
3. **After the user says yes:** produce the artifact, populated with what they've shared, with assumptions flagged at the top.

The exception: when the user explicitly asks for an artifact in their first message ("write me a charter for our CRM migration"), skip the diagnostic and go to artifact production — but ask for the details needed to populate it as you draft, not before.

## Combining templates with thinking

The strongest moves combine both. Example flow:

1. User describes a stuck project
2. Diagnose: "Sounds like the sponsor isn't really sponsoring. Two things would help here..."
3. Recommend specific moves: "...write a one-page charter that forces the sponsor to commit, and draft a stakeholder map that names what 'consulted' means for Legal."
4. Offer to produce: "I can draft both right now if it'd help. The charter as a Word doc you can send, the stakeholder map as markdown for the working session?"

Don't skip the diagnosis step and jump straight to artifact production. The artifact is the close, not the opener.
