# Contributing to Activation Greenhouse repositories

These defaults apply to every repository in the Activation Greenhouse Ltd (AGL) organisation unless a repository has its own `CONTRIBUTING.md`.

## Workflow

1. **Open an issue first.** Use one of the issue templates (feature, bug, task, proposal or growth experiment).
2. **Branch from `main`** using `{type}/{short-description}`, for example `feature/onboarding-audit` or `fix/tracking-plan-typo`.
3. **Commit in small steps** with clear messages in the imperative mood ("Add activation funnel dashboard").
4. **Open a pull request** using the PR template and link the issue (`Fixes #123`).
5. **Merge with squash** once checks pass and the PR is reviewed.

## Document naming

Documentation follows `{category}-{topic}-{type}.md`, where type is one of `plan`, `design`, `guide`, `runbook`, `analysis` or `incident`. For example: `acme-onboarding-funnel-analysis.md`.

## Confidentiality

Client work is confidential. Never commit:

- Credentials, API keys or tokens (use a password manager or GitHub secrets).
- Raw personal data or customer exports. Use aggregated or anonymised data only.
- Material covered by a client NDA in a repository that client has not been granted access to.

## Labels

Labels are managed centrally from the `agl-infra` repository. Do not create ad-hoc labels; propose new ones there.
