# Week 6 — Workflow Automation & Project Management

> n8n, Zapier, and Make.com, plus a comparison against Airtable/Asana/Trello/ClickUp for orchestration — the capstone week, tying every prior week's tools together into an actual automated pipeline.

![Status](https://img.shields.io/badge/Week-6%20of%206-success)
![Focus](https://img.shields.io/badge/Focus-Automation-blue)

## Objective

[PLACEHOLDER: 2–3 sentences — what were you trying to build this week? e.g. "Build one end-to-end automation that connects at least two tools from previous weeks (e.g. a new lead from Apollo triggering a Slack alert and a Mailchimp tag update), and understand the security implications of granting automation platforms broad API access across a stack."]

## Tools Covered

- n8n
- Zapier
- Make.com
- [PLACEHOLDER: which project management tool(s) you actually touched — Airtable, Asana, Trello, ClickUp, Monday, Zoho To Do]

## Projects

Documented in [`projects.md`](./projects.md):

1. **n8n workflow** — [PLACEHOLDER: one-line description]
2. **Zapier vs. Make.com comparison** — [PLACEHOLDER: one-line description]
3. **Project management tool** — [PLACEHOLDER: one-line description]

## Architecture

See [`diagrams/`](./diagrams/) for the exported diagram(s). This week's diagram is the one that matters most — it's the first time the individual platforms from Weeks 1–5 connect into a single system. Quick reference:

```
Trigger (e.g. new Apollo lead / new form submission)
  │
Automation Engine (n8n / Zapier / Make.com)
  │
Actions across connected tools:
  ├── CRM update
  ├── Slack/Teams notification
  ├── Email marketing tag
  └── Project management task creation
  │
Logging / Error Handling
```

## Exported Workflows

Raw workflow exports (JSON) live in [`workflows/`](./workflows/) — this is what makes this week's work verifiable rather than just described.

## Security Review

Full writeup in [`security-review.md`](./security-review.md).

## Lessons Learned & Retrospective

Full writeup in [`retrospective.md`](./retrospective.md).

## Demo

[PLACEHOLDER: short walkthrough video — this is the week most worth actually recording, since a working automation is much more convincing on video than in screenshots]

> Same trick as previous weeks: drag the video into a GitHub Issue comment box to get a CDN URL, then:
> ```html
> <video src="PASTE_GITHUB_CDN_URL_HERE" controls width="600"></video>
> ```

## References

- [PLACEHOLDER: docs, articles, or Medium post links for this week]

## Notes

Raw working notes: [`notes.md`](./notes.md)

---

## Programme Wrap-Up

This closes the six-week run. Once this week's placeholders are filled in, go back to the top-level `README.md` and:

- [ ] Update the status badge from `Week 6 of 6` to `Complete`
- [ ] Update the Weekly Progress table — all six rows should show ✅
- [ ] Write a short overall retrospective (a `retrospective.md` at the repo root, distinct from each week's) synthesizing what changed across all six weeks
- [ ] Link the two or three strongest weekly projects directly from the top-level README's "Projects" section, so a visitor doesn't have to click through all six weeks to see the best work
