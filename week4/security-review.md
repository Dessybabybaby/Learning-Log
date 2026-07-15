# Week 4 — Security Review: Mailchimp, Klaviyo, ActiveCampaign & Zoho Campaigns

## Identity

- **Authentication:** [PLACEHOLDER: MFA options, what you configured]
- **Authorization:** [PLACEHOLDER: team/user roles observed]
- **API Key Management:** [PLACEHOLDER: how API keys are generated/scoped/revoked — marketing platforms are frequently integrated via API, and leaked keys are a common real-world incident]

## Data Protection

- **PII Handling:** [PLACEHOLDER: what customer data lives in contact records — name, email, purchase history, custom fields]
- **Encryption:** [PLACEHOLDER: at-rest / in-transit]
- **List Import Controls:** [PLACEHOLDER: does the platform verify consent/opt-in on list uploads, or trust the uploader blindly?]

## Compliance

- **Consent & Opt-in:** [PLACEHOLDER: double opt-in support, unsubscribe handling]
- **CAN-SPAM / GDPR:** [PLACEHOLDER: what compliance tooling the platform provides — physical address requirement, unsubscribe footer, data subject deletion requests]
- **Audit Logs:** [PLACEHOLDER: what's logged — campaign sends, list changes, API access]

## Risks

- **Leaked API keys / webhooks:** [PLACEHOLDER: how easy would it be for a key to end up in a public repo or client-side code?]
- **Purchased/scraped lists:** [PLACEHOLDER: does the platform have any safeguard against non-consented lists being uploaded?]
- **Phishing-adjacent abuse:** [PLACEHOLDER: could the platform's sending reputation/domain be abused to send convincing phishing emails?]
- **Third-party integrations:** [PLACEHOLDER: what other tools (Shopify, CRM) does this connect to, and what data crosses that boundary?]

## Business Recommendations

[PLACEHOLDER: 2–4 concrete recommendations — e.g. API key rotation policy, double opt-in enforcement]

## Final Risk Rating

[PLACEHOLDER: Low / Medium / High, with one sentence justifying it]
