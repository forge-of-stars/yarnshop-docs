#yarnshop-docs
Yarn Shop SOPs — Docs-as-Code
Purpose: A repo of operational SOPs for online classes and shop processes, converted to a docs-as-code workflow to demonstrate reproducible documentation, testing, and CI.
What’s here: docs/sops/ — SOP markdown files per procedure; docs/templates/ — reusable templates (announcement, filename conventions); scripts/ — small utilities and runbook checklists; tests/ — automated tests validating scripts and examples; .github/workflows/ — CI that runs tests and link checks.
Quick start (WSL):
1. python3 -m venv .venv
2. . .venv/bin/activate
3. python -m pip install -r requirements.txt
4. make test
How to contribute: Fork, make edits in a feature branch, update the SOP version and changelog in the SOP file, run tests locally, open a pull request with a clear change description.
License: MIT
Contact: Orion Rozance — orion.rozance@gmail.com
