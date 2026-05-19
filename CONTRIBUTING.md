Contributing to Yarn Shop SOPs

Thank you for helping improve these SOPs. Please follow this workflow so changes are reviewable and reproducible.

Getting started
1. Fork the repository and clone your fork.
2. Create a feature branch named meaningfully, e.g., feature/clarify-payment-link.
3. Work in the docs/sops/<sop-name> folder for SOP edits and docs/templates for reusable files.

Editorial rules
- Keep each commit focused: one editorial change per commit.
- Use clear commit messages that reference the SOP and section (e.g., "sops/zoom-classes: clarify payment-link test step").
- Update the SOP front-matter meta: last_updated and version (increment minor patch, e.g., 0.1 → 0.2).
- Add or update a Changelog section in the SOP file for user-facing changes.

Testing & automation
- If you add scripts, include a pytest test under tests/ that validates the script behavior.
- Run tests locally before pushing: . .venv/bin/activate && pytest -q
- Ensure markdown links are valid and images live under docs/assets.

Pull request guidance
- Open a pull request from your feature branch to main.
- In the PR description, explain the change, link to the SOP section affected, and note any manual verification steps.
- Assign a reviewer and add the relevant label (documentation, editorial, automation).

Style & formatting
- Use clear, action-oriented language (imperative present tense).
- Prefer headings for process phases and numbered ordered steps for procedures.
- Use checklist markdown for runbook actions (- [ ]).

Licensing & sensitive data
- Do not include personal data, credentials, or payment information in the repo.
- If the change requires proprietary attachments, note them in the PR and add them to an approved private store instead.

Thank you
We appreciate careful, testable edits that keep SOPs accurate and auditable.
