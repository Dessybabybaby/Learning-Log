# Week 5 — Security Review: Apollo.io, Instant Data Scraper & Calendly

## Identity

- **Authentication:** [PLACEHOLDER: MFA options, what you configured]
- **Authorization:** [PLACEHOLDER: team/seat permissions in Apollo.io]
- **Browser Extension Permissions:** [PLACEHOLDER: what access Instant Data Scraper requests as a browser extension — this is worth scrutinizing, since scraper extensions typically request broad page-read permissions]

## Data Protection

- **Sourced Data Sensitivity:** [PLACEHOLDER: what kind of data is being collected — is any of it something the person didn't knowingly make public for this purpose?]
- **Storage:** [PLACEHOLDER: where the exported lead list ends up, and whether it's protected at rest]
- **Calendly Data:** [PLACEHOLDER: what booking data Calendly stores, and what's shared with invitees]

## Compliance

- **Legal basis for outreach:** [PLACEHOLDER: does the source data come with any usage restriction — Apollo's own terms, or the scraped site's ToS?]
- **Unsubscribe/opt-out handling:** [PLACEHOLDER: if this list feeds into Week 4's email tools, does it respect suppression lists?]
- **Audit Logs:** [PLACEHOLDER: what's logged on the Apollo.io side re: exports/searches]

## Risks

- **Scraping ToS/legal exposure:** [PLACEHOLDER: record what the target site's Terms of Service actually say about automated extraction — this is a real business risk, not just a technical one]
- **Stale/inaccurate data:** [PLACEHOLDER: how do you know the contact data is current? What's the error rate you observed?]
- **Browser extension over-permissioning:** [PLACEHOLDER: same theme as Week 3's OAuth app risk, applied to browser extensions instead]
- **Calendly link enumeration/spam:** [PLACEHOLDER: what happens if your booking link gets scraped and spammed with junk bookings?]

## Business Recommendations

[PLACEHOLDER: 2–4 concrete recommendations — e.g. always check a site's scraping policy before extracting, review browser extension permissions before installing]

## Final Risk Rating

[PLACEHOLDER: Low / Medium / High, with one sentence justifying it]
