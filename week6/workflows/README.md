# Workflows — Week 6

Raw exported workflow definitions (JSON) go here. This is the difference between "I say I built an automation" and "here's the actual automation, verifiable."

- **n8n:** Export via the workflow menu → Download. Produces a `.json` file you can drop in directly.
- **Zapier:** Zapier doesn't support raw JSON export the way n8n does — instead, take a clear screenshot of the full zap structure (steps + app icons visible) and reference it from `projects.md`.
- **Make.com:** Right-click the scenario canvas → Export Blueprint. Produces a `.json` file.

**Before committing:** open each JSON file and search for any API keys, tokens, or webhook URLs that might have been embedded during export. Redact them (replace with `REDACTED`) before pushing — exported automation files are a common accidental credential-leak vector, and this is worth calling out explicitly in your `security-review.md` too.

Suggested files:
- `n8n-lead-to-slack.json`
- `make-blueprint-export.json`
