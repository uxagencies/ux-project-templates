# Cheat Sheet

The one-pager. Decision guides, red flags, and plain-English definitions to go with the [templates](README.md).

---

## Which document do I need?

```
Are you still choosing an agency?
│
├─ Yes ──────────────────────────────►  RFP
│
└─ No, the partner is chosen.
   │
   ├─ Do we all agree on what "good" looks like yet?
   │  │
   │  ├─ No ──────────────────────────►  Design Brief
   │  │
   │  └─ Yes — now we're designing.
   │     │
   │     └─ Need to test an assumption with real users? ──►  UX Research Plan
```

One project usually needs all three, in that order. See the [lifecycle diagram](README.md#which-one-do-i-need).

---

## Which research method?

| Your question | Method | Roughly how many |
|---|---|---|
| *Why* do people behave this way? | In-depth interviews | 5–8 per segment |
| Can people actually *use* this? | Usability test (moderated) | ~5 per user group |
| Can people use it (fast, cheap, at scale)? | Unmoderated usability test | 15–30 |
| *How many* / *how often*? | Survey | Enough for significance (often 100s) |
| What do people already do? | Analytics, session replay | All your traffic |
| How do users *group / name* things? | Card sort / tree test | 15–30 |
| What's the experience *over days/weeks*? | Diary study | 8–15 |
| Does version A or B perform better? | A/B test | Enough traffic to reach significance |

> Rule of thumb: **qualitative** answers *why* and *how* (small N, deep). **Quantitative** answers *how many* and *which* (large N, shallow). Triangulate when the stakes are high.

---

## Red flags: is your document too vague?

**Your RFP is too vague if…**
- [ ] It names a solution ("build us an app") instead of a problem.
- [ ] There's no budget or range anywhere.
- [ ] "Success" isn't defined with a number.
- [ ] You haven't said what's *out* of scope.
- [ ] You're sending it to more than ~5 agencies.

**Your brief is too vague if…**
- [ ] You can't state the project in one sentence.
- [ ] No single person is named as the final approver.
- [ ] Objectives are outputs ("a redesign"), not outcomes ("+15% conversion").
- [ ] There are references but no *anti*-references.
- [ ] Nobody has signed off on it.

**Your research plan is too vague if…**
- [ ] You can't name the decision it informs.
- [ ] The questions could be answered without talking to a user.
- [ ] The method was chosen before the questions.
- [ ] There's no consent / data-handling section.
- [ ] You haven't said what you'll do if the findings are inconvenient.

---

## Reading a proposal: green flags vs. red flags

| Green flags 🟢 | Red flags 🔴 |
|---|---|
| Restates *your* problem in their own words | Generic intro that could be copy-pasted to anyone |
| Case studies match the *problem*, not just the industry | Logo wall with no outcomes |
| Names the actual team and their availability | Only senior names you'll never see again |
| Honest assumptions and what they need from you | Promises everything, asks for nothing |
| Pricing broken down by phase | One opaque number |
| Pushes back or reframes where warranted | Agrees with everything to win the deal |

---

## Glossary

- **RFP** — Request for Proposal. A document inviting agencies to propose how they'd solve your problem.
- **Design brief** — The shared agreement on goals, scope, and what "good" looks like, written once a project is underway.
- **Discovery** — Early-phase research and definition before solutions are designed.
- **IA** — Information architecture. How content and features are structured, labelled, and navigated.
- **JTBD** — Jobs To Be Done. Framing users by the *progress they're trying to make*, not demographics.
- **Usability testing** — Watching real users attempt real tasks to find where the design fails them.
- **Moderated / unmoderated** — A researcher present and asking questions vs. participants going solo via a tool.
- **WCAG** — Web Content Accessibility Guidelines; "WCAG 2.2 AA" is the common legal/target standard.
- **Design tokens** — Named, reusable values (colour, spacing, type) that keep design and code in sync.
- **Handoff** — Delivering design work to engineering in a build-ready form (specs, assets, tokens).
- **GDPR** — EU data-protection law; applies whenever you handle data about people in the EU/EEA.

---
*Part of the [UX & Design Project Templates](README.md) toolkit by [UXAgencies.com](https://uxagencies.com) · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)*
