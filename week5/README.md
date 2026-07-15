# Week 5 — Lead Generation & Appointment Setting

> Apollo.io, Instant Data Scraper, Yelp/Realtor.com sourcing, and Calendly, reviewed from a cybersecurity, SRE, and automation lens.

![Status](https://img.shields.io/badge/Week-5%20of%206-success)
![Focus](https://img.shields.io/badge/Focus-Lead%20Generation-blue)

## Objective

[PLACEHOLDER: 2–3 sentences — what were you trying to understand this week? e.g. "Understand how lead data is sourced, enriched, and handed off to a booking flow, and where the legal/ethical line sits on scraping public business data."]

## Tools Covered

- Apollo.io
- Instant Data Scraper
- Yellow Pages / Yelp / Realtor.com (as data sources)
- Calendly

## Projects

Documented in [`projects.md`](./projects.md):

1. **Apollo.io** — [PLACEHOLDER: one-line description of what you set up/tested]
2. **Instant Data Scraper** — [PLACEHOLDER: one-line description]
3. **Calendly** — [PLACEHOLDER: one-line description]

## Architecture

See [`diagrams/`](./diagrams/) for the exported diagram(s). Quick reference:

```
Source (Apollo.io / Yelp / Realtor.com)
  │
Extraction (native export / Instant Data Scraper)
  │
Enrichment & Dedup
  │
Lead List (CRM-ready)
  │
Booking Handoff (Calendly)
```

## Security Review

Full writeup in [`security-review.md`](./security-review.md).

## Lessons Learned & Retrospective

Full writeup in [`retrospective.md`](./retrospective.md).

## Demo

[PLACEHOLDER: short walkthrough video]

> Same trick as previous weeks: drag the video into a GitHub Issue comment box to get a CDN URL, then:
> ```html
> <video src="PASTE_GITHUB_CDN_URL_HERE" controls width="600"></video>
> ```

## References

- [PLACEHOLDER: docs, articles, or Medium post links for this week]

## Notes

Raw working notes: [`notes.md`](./notes.md)
