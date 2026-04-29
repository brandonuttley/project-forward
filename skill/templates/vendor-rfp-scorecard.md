# Vendor / RFP Scorecard

Structured evaluation of vendor proposals against weighted criteria. Forces the team to agree on what matters *before* seeing the responses, which prevents the all-too-common pattern of rationalizing toward a preferred vendor after the fact.

**When to use:** Any vendor selection involving more than two responses, material spend, or strategic implications. Especially valuable when the team has divergent views on what matters.

**When NOT to use:** Sole-source decisions. Tiny purchases. Renewals where the incumbent is performing well.

**Format default:** xlsx — this is fundamentally a scoring tool with calculations and filtering. Markdown works for the criteria-setting working session.

---

# [RFP Name] Vendor Scorecard

**Evaluation team:** [Names — typically 3-5 people across functions]
**Date:** [Evaluation date]
**Decision-maker:** [Sponsor or designated approver]

## Step 1: Define criteria and weights (BEFORE seeing responses)

Critical: agree on these before opening any vendor responses. Weights should sum to 100. Force trade-offs — if everything is "high priority," nothing is.

| # | Criterion | Weight | Definition / what we're evaluating | Why this weight |
|---|---|---|---|---|
| 1 | Functional fit | 25 | Does the solution do what we need it to do, out of the box, vs. requiring customization? | Highest weight — primary purpose |
| 2 | Total cost (3-year TCO) | 20 | All-in cost over 3 years: licensing, implementation, ongoing services, internal cost to maintain | Major budget impact, sustained over time |
| 3 | Implementation risk | 15 | Vendor's track record, reference quality, complexity of integration, dependencies on us | Major schedule and outcome risk |
| 4 | Security and compliance | 15 | Certifications (SOC 2, ISO 27001, etc.), data handling, regulatory fit | Non-negotiable in regulated environments |
| 5 | Vendor stability | 10 | Financial health, customer retention, leadership stability, product roadmap maturity | Longer-term concern |
| 6 | Support and SLAs | 10 | Response times, geographic coverage, escalation paths, dedicated resources | Operational quality of life |
| 7 | Cultural / partnership fit | 5 | Working style, communication, willingness to flex | Important but harder to assess pre-contract |
| **Total** | | **100** | | |

*Adjust criteria and weights to fit the specific RFP. The categories above are common starting points, not a fixed template.*

## Step 2: Score each vendor (1-5 scale)

**Scoring rubric:**
- **5 — Excellent:** Significantly exceeds requirements; differentiator vs. competitors
- **4 — Good:** Fully meets requirements with some strengths
- **3 — Acceptable:** Meets requirements; nothing that stands out
- **2 — Concerns:** Partially meets requirements; gaps that need mitigation
- **1 — Major concerns:** Doesn't meet requirements; would need significant compensating factors

| Criterion | Weight | Vendor A | Vendor B | Vendor C |
|---|---|---|---|---|
| Functional fit | 25 | | | |
| Total cost (3-year TCO) | 20 | | | |
| Implementation risk | 15 | | | |
| Security and compliance | 15 | | | |
| Vendor stability | 10 | | | |
| Support and SLAs | 10 | | | |
| Cultural / partnership fit | 5 | | | |

## Step 3: Calculate weighted scores

For each vendor: (Score × Weight) ÷ 5, summed across all criteria. Maximum possible score: 100.

| Vendor | Weighted total | Notes |
|---|---|---|
| Vendor A | | |
| Vendor B | | |
| Vendor C | | |

*In xlsx, this calculation is automatic. The formula in each weighted cell: `=Score*Weight/5`. Total: `=SUM(weighted_column)`.*

## Step 4: Disqualifiers (separate from scoring)

*Some criteria are pass/fail, not weighted. List them here. Any "Fail" knocks the vendor out regardless of weighted score.*

| Disqualifier | Vendor A | Vendor B | Vendor C |
|---|---|---|---|
| Required certifications (SOC 2 Type II, etc.) | Pass / Fail | | |
| Required data residency | | | |
| Required integration capability | | | |
| Reference checks (3 customers, no red flags) | | | |

## Step 5: Qualitative observations

*Numbers don't capture everything. Note the qualitative factors the scoring missed.*

**Vendor A:**
- Strengths: [What stood out positively]
- Concerns: [What stood out negatively]
- Reference feedback: [Themes from reference calls]
- Open questions: [What we still need to confirm]

**Vendor B:**
- Strengths:
- Concerns:
- Reference feedback:
- Open questions:

**Vendor C:**
- Strengths:
- Concerns:
- Reference feedback:
- Open questions:

## Step 6: Recommendation

*Don't lead with the winner. Walk through the analysis.*

**Recommended vendor:** [Name]

**Why:**
- [Top reason — usually the highest weighted criterion]
- [Second reason]
- [Third reason]

**Trade-offs accepted:**
- [What this vendor is weaker at, and why we're accepting that gap]
- [Any compensating action — e.g., "Will negotiate enhanced SLA in contract"]

**Why not the other vendors:**
- Vendor B: [Specific gap — not "less qualified" but "couldn't meet our data residency requirement"]
- Vendor C: [Specific gap]

## Step 7: Next steps

| Action | Owner | Due |
|---|---|---|
| Notify selected vendor | | |
| Notify non-selected vendors | | |
| Begin contract negotiation | | |
| Internal kickoff with implementation team | | |

---

## Notes for the PM

- **Set the criteria before opening responses.** This is the single most important discipline. Once you've seen the proposals, every criterion becomes "the thing the preferred vendor is good at."
- **Score independently first, then discuss.** Each evaluator scores on their own. *Then* the team meets to reconcile. If you discuss first, you anchor on the loudest voice.
- **Document the dissents.** When evaluators disagree on a score, capture both views. The disagreements often surface the most important questions.
- **Don't fear the "tie."** Two vendors scoring within a few points isn't a tie — it's a signal that the decision is closer than it looks. Use the qualitative observations and reference checks to break it.
- **Keep this artifact.** Six months in, when something goes wrong with the chosen vendor, the scorecard answers "did we make a defensible decision?" The answer being yes doesn't fix the problem, but it preserves trust.
