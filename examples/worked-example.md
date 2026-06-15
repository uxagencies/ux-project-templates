# Worked Example: Northbank

> [!NOTE]
> **Everything here is fictional.** "Northbank" is an invented digital bank used to show what each template looks like filled in *well* — and how the three documents hand off to one another across a single real-feeling project. Read it top to bottom to watch the story move from *choosing a partner* → *aligning on the work* → *validating with users*.

**The situation:** Northbank is a three-year-old mobile-only bank. Too many people who start opening an account never finish — completion sits at **38%**, and support is flooded with "I got stuck verifying my ID" messages. Leadership has approved budget to fix it and wants outside help.

---
---

# 1 · The RFP
*Northbank wrote this to invite agencies to pitch. Notice it describes the **problem**, not a solution.*

## About us
- **Company:** Northbank — a mobile-only consumer bank, ~600k customers across the EU.
- **Stage:** Series C, 180 people.
- **What prompted this now:** A board target to grow activated customers 25% this year; onboarding is the biggest leak.

## The opportunity
- **The problem:** 62% of people who begin account-opening abandon before finishing. The steepest drop is at identity verification.
- **What we've tried:** Shortened the form (helped slightly); added a progress bar (no measurable effect).
- **If we do nothing:** We keep paying to acquire users who never become customers — our biggest wasted spend.

## Goals & success metrics
| Goal | Measure | Baseline | Target |
|---|---|---|---|
| Lift onboarding completion | % who finish account-opening | 38% | 60% |
| Cut ID-related support tickets | Tickets/week tagged 'verification' | 240 | < 100 |

## Scope
- **In scope:** Discovery, redesign of the end-to-end account-opening flow, dev-ready handoff.
- **Out of scope:** Native development, the marketing site, ongoing maintenance.
- **Existing assets:** A maintained design system (Figma) and 18 months of funnel analytics.

## Budget & timeline
- **Range:** €70,000–95,000.
- **Decision by:** 30 September; kickoff mid-October.

## How we'll evaluate
| Criterion | Weight |
|---|---|
| Understanding of the problem | 30% |
| Relevant case studies (fintech / regulated onboarding) | 25% |
| Approach & named team | 25% |
| Value for budget | 15% |
| Working-style fit | 5% |

> **Outcome:** five agencies were invited; three proposed. Northbank selected **a studio whose case study showed a near-identical KYC drop-off problem** — not the one with the flashiest logo wall. On to the brief.

---
---

# 2 · The Design Brief
*Written together by Northbank and the chosen agency at kickoff. This is where they agreed what "good" means.*

> **The one-liner:** *We are rebuilding account-opening for first-time mobile users so that more of them finish in one sitting.*

## Objectives
- **Primary:** Lift completion from **38% → 60%** within two quarters.
- **Secondary:** Reduce verification support tickets by 60%; don't increase fraud rate.

## Success metrics
| Metric | Baseline | Target | Measured |
|---|---|---|---|
| Onboarding completion | 38% | 60% | Funnel analytics, post-launch |
| Time to complete | 11 min median | < 7 min | Analytics |
| Verification ticket volume | 240/wk | < 100/wk | Support tags |

## Audience
- **Primary:** First-time applicants on mobile, often opening their first "main" account, frequently mid-task and distracted.
- **Key job-to-be-done:** "Get a working account today without digging out documents I don't have on me."

## Scope
- **In scope:** Every screen from "Open an account" to "Account ready," including the ID-verification handoff.
- **What we're *not* changing:** The third-party KYC provider (contractually fixed for 18 months) — the design must work *around* its constraints.

## Anti-references
- **Anti-reference:** *Most challenger banks front-load every detail and legal disclosure. We want the opposite — let people experience value before we ask for the hard stuff, and never show two heavy steps back to back.*

## Experience principles
- One decision per screen.
- Earn trust before asking for sensitive data.
- A dead end always offers a way forward (save, retry, or talk to us).

## Stakeholders & decisions
| Role | Name | Involvement |
|---|---|---|
| Final decision-maker | VP Product (Lena) | Signs off direction & final designs |
| Consulted | Compliance, Fraud, Eng lead | Input at each phase gate |

> **Outcome:** the team designed a new flow that defers ID verification until after the account shell is created. But they weren't sure users would trust a "verify later" prompt — so before committing engineering, they planned research.

---
---

# 3 · The UX Research Plan
*Run mid-design to de-risk one specific assumption before build.*

## The decision at stake
Should we ship the **"create account first, verify later"** flow as designed, or does deferring verification create confusion or drop-off of its own? *Decision owner: Lena (VP Product).*

## Goals & research questions
**Goal:** Understand how first-time users react to deferred verification.

**Research questions:**
- Where do users hesitate or fail in the new flow?
- What do users *expect* will happen when they tap "Verify later," and does the result match?
- At what point, if any, do users worry the account "isn't real yet"?

**Assumption being tested:** *We believe deferring verification will raise completion because people can act before hunting for documents. We could be wrong if it instead reads as untrustworthy.*

## Method & rationale
- **Method:** Moderated usability test on an interactive prototype, remote.
- **Why:** We need to see *where people stumble and why* — a behavioural, qualitative question, not a numbers question.

## Participants
- **Who:** 6 people who have opened a bank account on mobile in the last year and aren't current Northbank customers.
- **Recruitment:** External panel, screened. €60 incentive.

## Ethics & data handling
- [x] Informed consent, recording explained, right to stop anytime.
- [x] Recordings stored access-limited; deleted after 90 days.
- [x] Findings anonymised. **GDPR lawful basis: consent.**

## Deliverables
- One-page summary, a prioritised list of issues, and three highlight clips for the readout. **Success = Lena makes a confident ship / rework call.**

## What we'll do with the findings
- **If they support the design:** proceed to build as planned.
- **If they contradict it:** rework the "verify later" moment — likely adding a clearer "your account is active, this just unlocks transfers" reassurance — *before* engineering starts, not after.

> **Outcome (illustrative):** 5 of 6 users completed the flow comfortably, but several hesitated at "Verify later," unsure if their account was real. The team added a one-line reassurance and a status chip — a cheap change, caught *before* code. That's the whole point of doing this in order.

---
---

*This is a fictional illustration for the [UX & Design Project Templates](../README.md) toolkit by [UXAgencies.com](https://uxagencies.com). Grab the blank [RFP](../rfp-template.md), [brief](../design-brief-template.md), and [research plan](../ux-research-plan-template.md) to start your own.*
