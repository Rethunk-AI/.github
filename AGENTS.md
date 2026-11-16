# AGENTS.md

Org defaults for Rethunk-AI: the public org profile and the community health files for repos here that have none of their own. `profile/README.md` is the org landing page; the root `README.md` describes this repo.

## Layout

- `profile/README.md`: the org page, with the Active table of repos and the links to sibling orgs (Rethunk-Tech, Citadel-Inc).
- `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `SECURITY.md`, `SUPPORT.md`: org-wide defaults.
- `.github/workflows/`: CodeQL, dependency review, OpenSSF Scorecard. `.github/dependabot.yml` for the actions.
- `lefthook.yml` and `.gitleaks.toml`: pre-commit secret scan.

## Verify

No build. Run `gitleaks git --redact --no-banner`, then open each repo link in the profile after editing the table.

## Invariants

- The profile lists only repos that exist and are public. When one is created, archived or made private, update the table in the same commit.
- The legal name is "Rethunk.Tech, LLC", never "Rethunk Technologies".
- Actions are pinned to a full commit SHA.
