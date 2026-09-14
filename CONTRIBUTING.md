# Contributing

Thanks for considering a contribution to [Rethunk-AI](https://github.com/Rethunk-AI).
This is the **organization default**. If a repository ships its own
`CONTRIBUTING.md` (or `HUMANS.md` / `AGENTS.md`), follow those first.

## Ground rules

- Be respectful — see [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md).
- Keep changes focused: one logical unit per PR when practical.
- Prefer fixing docs and tests alongside behavior changes.
- Do not commit secrets, credentials, or private customer data.

## Commits

Use [Conventional Commits](https://www.conventionalcommits.org/):

```text
type(scope): subject
```

Common types: `feat`, `fix`, `docs`, `refactor`, `test`, `ci`, `build`, `chore`.
The body should explain **why**, not restate the diff.

## Pull requests

1. Branch from the repository default branch (`main` unless noted).
2. Run the project's documented checks (CI, `lefthook`, `gate`, etc.) before asking for review.
3. Describe: what changed, why, how you tested, and any deliberate tradeoffs.
4. Link related issues.

## Security

Report vulnerabilities privately — see [`SECURITY.md`](SECURITY.md).

## Questions

- Project-specific: open an issue on that repo
- Org / process: [oss@rethunk.ai](mailto:oss@rethunk.ai) or see [`SUPPORT.md`](SUPPORT.md)
