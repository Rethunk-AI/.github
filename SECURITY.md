# Security Policy

This is the **organization default** for [Rethunk-AI](https://github.com/Rethunk-AI).
If a repository has its own `SECURITY.md`, follow that file instead.

## Supported versions

Unless a repo says otherwise, only the default branch (`main`) is supported.
Security fixes land there; there is typically no long-lived release branch.

## Reporting a vulnerability

**Do not open a public issue** for security-sensitive findings.

1. Prefer GitHub's private advisory flow on the affected repository:
   `https://github.com/Rethunk-AI/<repo>/security/advisories/new`
2. If that is unavailable, email [oss@rethunk.ai](mailto:oss@rethunk.ai) with
   **[SECURITY]** in the subject.

Please include:

- Affected repository and commit SHA (or release tag)
- Reproduction steps
- Observed vs. expected behavior
- Impact assessment (local-only, requires credentials, remote exploitability, etc.)

We aim to acknowledge reports within a few business days.

## Scope guidance

**Usually in scope**

- Remote or local code execution reachable through project code or config
- Credential or secret leakage via logs, artifacts, or docs
- Supply-chain issues in first-party packaging or release signing we control
- Authz / sandbox bypasses in agent tooling we publish

**Usually out of scope**

- Issues that require already having root or physical access to the host
- Bugs solely in upstream dependencies without a demonstrable path through our code
  (report those upstream; link us if relevant)
- Denial of service from intentional oversized local workloads (resource sizing)
- Social-engineering of individual maintainers outside published channels

## Safe harbor

We will not pursue legal action against good-faith research that:

- Avoids violating privacy, destroying data, or degrading production services
- Stops at proof of concept without exfiltrating unrelated user data
- Gives us a reasonable chance to remediate before public disclosure
