# Week 2 — File Management & Cloud Storage

> Dropbox and Zoho WorkDrive, reviewed from a cybersecurity, SRE, and automation lens.

![Status](https://img.shields.io/badge/Week-2%20of%206-success)
![Focus](https://img.shields.io/badge/Focus-File%20Management-blue)

## Objective

[PLACEHOLDER: 2–3 sentences — what were you trying to understand about Dropbox / Zoho WorkDrive this week? e.g. "Understand how file-sharing permissions and sync behave across two different cloud storage platforms, and where data leakage risk creeps in."]

## Tools Covered

- Dropbox
- Zoho WorkDrive
- [PLACEHOLDER: note if you revisited Google Drive/M365 storage here too — Week 1 covered the identity layer, Week 2 can go deeper on the storage/sharing layer]

## Projects

Documented in [`projects.md`](./projects.md):

1. **Dropbox** — [PLACEHOLDER: one-line description of what you set up/tested]
2. **Zoho WorkDrive** — [PLACEHOLDER: one-line description]

## Architecture

See [`diagrams/`](./diagrams/) for the exported diagram(s). Quick reference:

```
Users
  │
Cloud Storage (Dropbox / Zoho WorkDrive)
  │
Sync Clients / Web Access
  │
Sharing Layer (links, folders, team spaces)
  │
Admin Console / Compliance Center
```

## Security Review

Full writeup in [`security-review.md`](./security-review.md).

## Lessons Learned & Retrospective

Full writeup in [`retrospective.md`](./retrospective.md).

## Demo

[PLACEHOLDER: short walkthrough video]

> Same trick as Week 1: drag the video into a GitHub Issue comment box to get a CDN URL, then:
> ```html
> <video src="PASTE_GITHUB_CDN_URL_HERE" controls width="600"></video>
> ```

## References

- [PLACEHOLDER: docs, articles, or Medium post links for this week]

## Notes

Raw working notes: [`notes.md`](./notes.md)
